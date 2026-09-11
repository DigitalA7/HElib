# 05 — Clés, sérialisation et limites

La clé secrète contrôle le déchiffrement ; les clés publiques et d’évaluation élargissent les opérations possibles.
Distribuer une clé d’évaluation ne doit pas être confondu avec distribuer le secret.
Les contextes, chiffrés et clés sérialisés doivent conserver leurs paramètres compatibles.
Une application doit authentifier provenance, version et intégrité de ces artefacts.
La FHE protège le contenu, pas automatiquement tailles, accès ou métadonnées temporelles.
Ce parcours couvre BGV, CKKS, packing, bruit, niveaux, bootstrapping et clés.
Il ne constitue ni sélection de paramètres certifiée ni audit cryptographique.
Aucune installation, compilation ou exécution n’a été effectuée ; les tests amont restent la référence.
