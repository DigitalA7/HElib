# 03 — Bruit, niveaux et transformations

Chaque opération homomorphe modifie le bruit et le module courant du chiffré.
Les multiplications réduisent plus vite la marge disponible.
La relinéarisation ramène la taille après multiplication au moyen de clés dédiées.
Le modulus switching descend la chaîne de modules pour contrôler les paramètres.
Dans CKKS, rescaling et échelle numérique doivent rester alignés.
Un circuit trop profond échoue au déchiffrement ou perd la précision attendue.
Le budget doit suivre le pire chemin, y compris rotations et conversions.
Les métriques de bruit appartiennent aux critères d’acceptation du calcul.

Suite : [bootstrapping](04-bootstrapping.md).
