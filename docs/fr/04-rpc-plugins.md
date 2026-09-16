# 04 — JSON-RPC et plugins

Nethermind expose JSON-RPC sur HTTP, WebSocket et IPC. Les modules RPC regroupent les méthodes par espaces de noms et relient les requêtes à l’état, au pool de transactions ou au moteur d’exécution.

Le système de plugins est une frontière d’extension centrale. Une implémentation `INethermindPlugin` peut enregistrer des services, des modules RPC, des protocoles réseau ou un moteur de consensus, puis être chargée au démarrage.

Cette architecture sert aussi les réseaux L2 : leur logique peut vivre dans un plugin pendant que le noyau conserve ses invariants communs. La compatibilité RPC reste toutefois dépendante de la version et de la configuration.

[Chapitre suivant : observation et performance →](05-observation-performance.md)
