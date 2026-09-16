# 06 — Sécurité, exploitation et limites

Le dépôt fournit une politique de sécurité et plusieurs couches de validation : consensus, transactions, blocs, état et interfaces. Les licences LGPL et les fichiers de licence associés encadrent la redistribution.

Un opérateur doit isoler les ports RPC, protéger les clés du validateur, limiter les méthodes sensibles et surveiller le stockage. Les plugins augmentent la surface de confiance : leur code et leurs dépendances doivent être examinés comme le client lui-même.

Ce parcours reste documentaire : il décrit les mécanismes visibles dans la branche `master` sans installation, compilation ni exécution de test. Pour vérifier les comportements, consulter la suite de tests et les workflows du dépôt.

[Retour au sommaire →](README.md)
