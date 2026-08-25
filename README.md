# Cursus systèmes complexes — Terrain d'entraînement : le système agricole français

Dépôt public de travail personnel de montée en compétence sur la pensée des
systèmes complexes, appliquée au système agricole français comme terrain
d'entraînement (voir `docs/avant_propos.md`).

**Ce dépôt n'est pas un outil de conseil ni une position politique arrêtée.**
Il documente une démarche d'apprentissage, avec ses hypothèses, ses erreurs et
ses corrections. Toute contribution, critique ou signalement d'erreur via les
Issues GitHub est bienvenu — c'est même l'un des objectifs du dépôt : sortir
le travail d'un dialogue fermé.

## Règle de méthode

Chaque bloc et chaque livrable cherche d'abord les conditions dans lesquelles
l'hypothèse de départ est fausse. Voir `registre_hypotheses/` pour la trace
de cette discipline.

## Structure

- `docs/` — avant-propos, contenu détaillé de chaque bloc
- `registre_hypotheses/` — journal vivant des hypothèses testées/infirmées/confirmées
- `bloc00_cadrage/` à `bloc11_projet_integrateur_fas_fr/` — un dossier par bloc :
  code, notebooks, notes, livrables
- `data/raw/` — données brutes (non versionnées par défaut, voir `.gitignore`
  et `DATA_LICENSE.md`)
- `data/processed/` — données nettoyées réutilisées entre blocs

## Avancement

| Bloc | Titre                                             | Statut       |
|------|----------------------------------------------------|--------------|
| 0    | Cadrage et diagnostic                              | à démarrer   |
| 1    | Pensée systémique (Meadows)                        | à démarrer   |
| 2    | System Dynamics (Sterman) — FARM-SD v0.1           | à démarrer   |
| 3    | Refresh quantitatif ciblé                          | à démarrer   |
| 4    | Microéconomie et économie politique                | à démarrer   |
| 5    | Économétrie et causalité                           | à démarrer   |
| 6    | Complexité et réseaux                              | à démarrer   |
| 7    | Optimisation et arbitrages multi-objectifs         | à démarrer   |
| 8    | Incertitude et décision robuste                    | à démarrer   |
| 9    | Analyse institutionnelle française                 | à démarrer   |
| 10   | Reverse engineering CAPRI + confrontation débat réel| à démarrer  |
| 11   | Projet intégrateur — FAS-FR v0.1                   | à démarrer   |

## Installation

\`\`\`bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
\`\`\`

## Licence

Code sous licence MIT (voir `LICENSE`). Données sous leurs licences d'origine
respectives (voir `DATA_LICENSE.md`) — jamais republiées sans vérification.
