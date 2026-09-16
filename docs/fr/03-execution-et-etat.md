# 03 — Exécution EVM et état

Le traitement d’un bloc valide les en-têtes, exécute les transactions et persiste le nouvel état. Les abstractions `IWorldState`, le processeur de blocs et les spécifications de fork séparent la logique de transition des détails de stockage.

L’exécution gère les comptes, le code, le stockage et les journaux. Les scopes d’état rendent possibles les lectures isolées, les simulations et les retours arrière contrôlés.

Le dépôt contient aussi des chemins d’exécution stateless et des outils de test de vecteurs Ethereum. Ils montrent comment les racines d’état et les erreurs d’exécution servent de contrats vérifiables.

[Chapitre suivant : RPC et plugins →](04-rpc-plugins.md)
