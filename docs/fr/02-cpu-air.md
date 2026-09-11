# 02 — CPU AIR et contraintes Cairo

Le dossier `src/starkware/air/cpu` relie la sémantique Cairo à des contraintes algébriques.
Registres, mémoire et transitions d’instructions doivent évoluer de façon cohérente.
La trace seule n’est pas une preuve : elle devient crédible lorsque toutes les identités sont satisfaites.
Les contraintes de bord fixent les états initial et final attendus.
Les contraintes de transition encadrent chaque pas entre deux lignes.
Les arguments de permutation relient des accès dispersés à une vue cohérente de la mémoire.
Une omission dans l’AIR peut accepter une trace qu’aucune exécution valide ne produirait.
La revue doit donc comparer chaque règle CPU à sa traduction polynomiale.

Suite : [engagements de Merkle](03-engagements-merkle.md).
