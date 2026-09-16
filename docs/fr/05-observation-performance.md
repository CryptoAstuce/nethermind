# 05 — Observation et performance

Le runner fournit des signaux d’exploitation via l’interface de santé, les logs et Prometheus. Le flux de données de monitoring peut exposer progression, traitement et choix de tête selon les abonnements.

La performance vient de plusieurs niveaux : dispatch EVM, structures de données, RocksDB, prélecture parallèle et réglages du ramasse-miettes. Les benchmarks et tests du dépôt documentent ces chemins sans remplacer une mesure sur l’environnement réel.

Les métriques doivent être reliées à une hypothèse opérationnelle : retard de synchronisation, saturation RPC, temps de traitement ou pression mémoire. Une alerte isolée ne suffit pas à diagnostiquer un nœud.

[Chapitre suivant : sécurité et limites →](06-securite-limites.md)
