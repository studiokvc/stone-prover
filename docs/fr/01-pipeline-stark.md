# 01 — Le pipeline STARK

Stone contient un prouveur et un vérificateur pour le CPU AIR de CairoZero.
Le programme exécuté devient une trace structurée en colonnes.
L’AIR décrit les identités que cette trace doit respecter.
Le prouveur engage la trace avant de recevoir les défis du protocole.
La composition regroupe ensuite les contraintes en un polynôme contrôlable.
FRI établit que les objets engagés ont le faible degré attendu.
Le vérificateur ne rejoue pas toute l’exécution : il contrôle des ouvertures échantillonnées.
Cette réduction explique l’intérêt des STARK pour les calculs volumineux.

Suite : [CPU AIR et contraintes](02-cpu-air.md).
