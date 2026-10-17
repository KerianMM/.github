# Fichiers communs à mes dépôts

Ce dépôt fournit les **modèles d'issue par défaut** de tous mes dépôts qui n'ont pas les leurs.

## Modèles

- **Fonctionnalité** : Besoin, Objectif, Prérequis, Résolution, Critères d'acceptation, Hors périmètre, Sources, Questions ouvertes. Seuls **Besoin, Objectif et Critères d'acceptation** sont indispensables ; le reste s'utilise si pertinent.
- **Idée** : Besoin et Questions ouvertes, pour noter une idée rapidement.
- Les issues vierges restent possibles.

## Cycle de vie d'une issue

1. **`à discuter`** : l'issue est rédigée et discutée. Elle peut commencer comme une simple idée.
2. **`prête`** : elle a un objectif, des critères d'acceptation vérifiables, et **plus aucune question ouverte**.
3. **Développement** par `@claude`, pull request qui référence l'issue (`Closes #n`), CI au vert, merge.

## À savoir

- Les labels `à discuter` et `prête` doivent exister dans chaque dépôt qui utilise ces modèles.
- Un dépôt qui définit ses propres modèles n'utilise plus aucun de ceux-ci.
- Ce dépôt doit rester **public** : n'y mets rien de confidentiel.