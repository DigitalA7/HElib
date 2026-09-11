# 02 — Packing et calcul SIMD

HElib place plusieurs valeurs logiques dans les slots d’un même chiffré.
Une addition ou multiplication agit alors en parallèle sur tous les slots.
Les rotations déplacent les slots pour agréger ou permuter les données.
Elles nécessitent des clés d’évaluation spécifiques et consomment des ressources.
Le mapping entre indices métier et slots doit être documenté explicitement.
Une rotation correcte cryptographiquement peut être fausse fonctionnellement.
Les masques en clair sélectionnent les positions utiles après permutation.
Le packing est donc à la fois une optimisation et une partie du programme.

Suite : [bruit et niveaux](03-bruit-niveaux.md).
