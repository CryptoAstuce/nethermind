# 01 — Le rôle de Nethermind

Nethermind est un client d’exécution Ethereum écrit principalement en C#. Il reçoit des blocs et des transactions, maintient l’état et expose des interfaces JSON-RPC. Le dépôt sépare le noyau, le runner, les plugins, les bases de données et les composants de test.

Le point d’entrée assemble la configuration, les services et les plugins avant de démarrer le nœud. Cette composition permet de prendre en charge Ethereum mais aussi plusieurs réseaux compatibles sans modifier le cœur.

La lecture utile commence dans `src/Nethermind/`, notamment le runner et les modules d’initialisation. Le README décrit aussi les capacités d’exploitation et le rôle de la diversité des clients.

[Chapitre suivant : synchronisation →](02-synchronisation.md)
