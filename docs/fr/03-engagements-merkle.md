# 03 — Engagements de Merkle

Les couches de données sont engagées par des arbres de Merkle avant l’échantillonnage.
Une racine lie le prouveur à l’ensemble des feuilles sans toutes les révéler.
Chaque ouverture transporte la valeur demandée et son chemin d’authentification.
Le vérificateur recalcule la racine et rejette toute branche incohérente.
L’indexation des feuilles et le format de sérialisation font partie du protocole.
Une racine correcte ne prouve toutefois pas que les valeurs respectent l’AIR.
Elle garantit seulement que les réponses restent cohérentes avec l’engagement initial.
Merkle et contraintes jouent ainsi deux rôles complémentaires.

Suite : [FRI et faible degré](04-fri-securite.md).
