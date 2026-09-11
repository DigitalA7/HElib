# 01 — Deux sémantiques de calcul chiffré

HElib prend en charge BGV et CKKS avec des objectifs différents.
BGV convient à l’arithmétique modulaire exacte sur des entiers.
CKKS encode des nombres réels ou complexes avec une erreur approximative.
Le choix détermine ce qu’un résultat déchiffré signifie.
Une égalité métier stricte ne doit pas reposer sur une approximation non bornée.
Le contexte fixe anneau, module, sécurité et niveaux disponibles.
Les exemples de démonstration ne constituent pas des paramètres de production.
Le calcul attendu doit être décrit avant de choisir le schéma.

Suite : [packing SIMD](02-packing-simd.md).
