# Exercice 1.2 — Résumé des 10 boucles causales fermées

Règle de classification : on compte le nombre de signes négatifs le long de la boucle complète.
**Pair (0, 2, 4...) → boucle Renforçante (R)**. **Impair (1, 3, 5...) → boucle Équilibrante (B)**.

Deux règles de construction appliquées à l'ensemble des 10 boucles, issues des échanges de correction :
1. **Un stock ne peut jamais agir directement sur un autre stock.** Chaque flèche stock→stock a été
   remplacée par un flux explicite (ex. « Achat outil ») ou un lien d'information explicite (ex. une
   décision fondée sur le niveau du stock).
2. **Une variable exogène (qui influence le système sans être influencée en retour) ne fait pas partie
   de la boucle.** Elle apparaît comme une entrée séparée, pas comme un maillon du cycle qui se referme.

---

### B1 — Trésorerie → Outil → Production → Trésorerie — **Renforçante (R)**
Trésorerie → Achat outil (+) → Stock Outil (+) → Capacité de production (+) → Production (+) →
Vente (+) → Trésorerie (+). **0 signe négatif → R.**
Boucle de croissance classique par investissement — s'auto-amplifie tant que rien ne la limite.

### B2 — Investissement foncier → Dette → Trésorerie → Investissement foncier — **Équilibrante (B)**
Investissement foncier (+) → Dette (+) → Remboursement annuel (+) → Trésorerie disponible (**–**) →
Capacité à investir (+) → Investissement foncier (+). **1 signe négatif → B.**
L'endettement se freine lui-même : plus on emprunte, moins il reste de capacité à réinvestir.

### B3 — Gestion du stock d'hydrocarbure — **Équilibrante (B)**
Stock hydrocarbure (**–**) → Écart au stock cible (+) → Décision de réapprovisionnement (+) →
Achat hydrocarbure (+) → Stock hydrocarbure (+). **1 signe négatif → B.**
Boucle de gestion de stock classique, orientée vers un objectif (goal-seeking).

### B4 — Gestion du stock d'aliments — **Équilibrante (B)**
Même structure que B3, appliquée au stock grain/aliment. **1 signe négatif → B.**

### B5 — Fertilité → rendement → réinvestissement en engrais — **Renforçante (R)**
Fertilité du sol (+) → Rendement (+) → Production (+) → Vente (+) → Trésorerie (+) →
Achat engrais (+) → Épandage (+) → Fertilité du sol (+). **0 signe négatif → R.**
Cercle vertueux (ou vicieux si on part d'une baisse de fertilité) d'intensification.

### B6 — Fertilité → sur-fertilisation → lessivage — **Équilibrante (B)**
Fertilité (+) → Rendement (+) → Sur-fertilisation (+) → Lessivage (+) → Fertilité (**–**).
**1 signe négatif → B.**
**À lire avec B5** : les deux boucles agissent sur le même stock (fertilité) en sens opposé. Tant que la
fertilité est loin de son plafond, B5 (croissance) domine. À l'approche du plafond agronomique,
B6 (limite) prend le dessus. C'est l'archétype « Limits to Growth » de Meadows, avec un exemple
agricole concret.

### B7 — Compétences → efficacité → recrutement — **Renforçante (R)**
Main d'œuvre (+) → Compétences (+) → Efficacité (+) → Production (+) → Trésorerie (+) →
Capacité à recruter/former (+) → Main d'œuvre (+). **0 signe négatif → R.**
Peut jouer en cercle vertueux (montée en compétence) ou vicieux (érosion après un départ mal
remplacé) — une boucle renforçante amplifie la direction initiale, quelle qu'elle soit.

### B8 — Réseau professionnel → temps → production — **Équilibrante (B)**
Capital social (+) → Sollicitations reçues (+) → Temps consacré au réseau (+) →
Temps disponible pour l'exploitation (**–**) → Production (+) → Trésorerie (+) →
Capacité à s'investir dans le réseau (+) → Capital social (+). **1 signe négatif → B.**
Le réseau a un coût d'opportunité en temps qui finit par freiner son propre entretien.

### B9 — Réseau professionnel → conditions de crédit → marge — **Renforçante (R)**
Trésorerie (+) → Capacité à investir dans le réseau (+) → Capital social (+) →
Conditions de prêt/accès aux intrants (+) → Marge (+) → Trésorerie (+). **0 signe négatif → R.**
**À lire avec B8** : même stock (capital social), deux mécanismes opposés — l'un renforce
(meilleur accès au crédit), l'autre freine (coût d'opportunité en temps). Lequel domine dépend du
contexte, exactement comme B5/B6 sur la fertilité.

### B10 — Croissance structurelle par le foncier — **Renforçante (R)**
Foncier (+) → Surface cultivée (+) → Production (+) → Vente (+) → Trésorerie (+) →
Investissement foncier (+) → Foncier (+). **0 signe négatif → R.**
Archétype « le succès nourrit le succès » — pertinent pour le débat sur l'agrandissement structurel
des exploitations françaises (utile pour le Bloc 9).

---

## Bilan

- **5 boucles renforçantes (R)** : B1, B5, B7, B9, B10.
- **5 boucles équilibrantes (B)** : B2, B3, B4, B6, B8.
- **10 stocks de l'exercice 1.1 réutilisés** sur les 10 boucles (largement au-dessus du minimum de 6) :
  Trésorerie, Dette, Foncier, Fertilité du sol, Hydrocarbure, Stock grain et aliment, Outil, Engrais,
  Main d'œuvre, Compétences, Capital social/réseau, Stock céréale.
- Note : « Stock céréale » et « Stock aliments » sont ici traités comme une scission utile du stock
  unique « Stock grain et aliment » de l'exercice 1.1 (l'un est vendu, l'autre consommé en interne —
  deux flux de sortie assez différents pour justifier de les distinguer). À reporter dans le tableau 1.1
  si cette distinction est conservée pour la suite.
- Trois paires de boucles opposées sur un même stock (B5/B6 sur la fertilité, B8/B9 sur le capital
  social) — bon matériau pour illustrer au Bloc 2 la notion de **dominance de boucle qui change dans
  le temps**, cœur du comportement en S des systèmes réels.
