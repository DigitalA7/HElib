# 04 — Bootstrapping et rafraîchissement

Le bootstrapping évalue le déchiffrement sous chiffrement pour restaurer la capacité de calcul.
HElib implémente cette opération notamment pour BGV.
La procédure dépend fortement de la structure de l’anneau et du packing.
Elle exige des données préparées et des clés d’évaluation supplémentaires.
Son coût peut dominer très largement celui des opérations ordinaires.
La fréquence de rafraîchissement doit être prévue dans la conception du circuit.
Un rafraîchissement réussi ne corrige pas une erreur de logique ou d’encodage.
Il renouvelle le budget cryptographique du chiffré.

Suite : [clés et limites](05-cles-limites.md).
