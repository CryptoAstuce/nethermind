# 02 — Synchronisation et disponibilité

Les composants de synchronisation coordonnent découverte des pairs, téléchargement et rattrapage de la chaîne. Le README met en avant Snap Sync, activé par défaut, qui reconstruit l’état en combinant données historiques et nouveaux blocs.

Le pipeline doit distinguer les en-têtes, les corps, les reçus et l’état afin de ne pas bloquer inutilement la progression. Les files et les pairs permettent de paralléliser les demandes tout en respectant les contraintes de validité.

Les options de synchronisation sont assemblées avec la configuration du client et observables via les métriques. Le détail de la convergence dépend du réseau, du stockage et de la qualité des pairs.

[Chapitre suivant : exécution EVM →](03-execution-et-etat.md)
