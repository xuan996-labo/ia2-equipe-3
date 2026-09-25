# Équipe 3

## 1. Présentation du projet

### 1.1 Objectif du projet

Cette équipe travaille sur les exercices 3.1 et 3.3 portant sur les arbres et l'algorithme de Dijkstra.


### 1.2 Description du projet

Ce projet consiste à réaliser en équipe trois exercices de révision portant sur les arbres, les graphes et l’algorithme de Dijkstra.

Chaque membre de l’équipe prend en charge un exercice, puis explique sa solution aux autres membres afin que toute l’équipe puisse comprendre et maîtriser les différentes notions.

Les trois exercices de l’équipe 3 sont :

- **3.1** — Arbre binaire : du dessin à la liste - Xuan
- **3.2** — Graphe : du dictionnaire au dessin
- **3.3** — Dijkstra : à partir d’une matrice - Laura
---

## 2. Membres de l'équipe

- Laura Sorro
- Xuan Wang
---
## Répartition du travail

| Membre | Responsabilités |
|---|---|
| Xuan Wang | Partie 3.1 |
| Laura Sorro | Partie 3.3 |

## 3. Réalisation du projet

### 3.1 Xuan  — Arbre binaire : du dessin à la liste

> **Responsable : Xuan**

L'exercice 3.1 consiste à partir d'un arbre binaire représenté sous forme de dessin et à construire sa représentation sous forme de liste Python.

#### 3.1.a Travail réalisé

- Analyse de l’arbre binaire à partir de sa représentation graphique.
- Identification de la position de chaque nœud dans la liste.
- Transformation de l’arbre en une liste Python en respectant la règle des indices :
  - enfant gauche : `2i + 1`
  - enfant droit : `2i + 2`
- Identification des cases `None` nécessaires pour conserver la structure de l’arbre.
- Réalisation du parcours en largeur, niveau par niveau et de gauche à droite.
- Identification des feuilles, des branches et du nombre de niveaux.

| Nœud | J | D | T | A | G | W | E | U  |
| ---- | - | - | - | - | - | - | - | -- |
| Case | 0 | 1 | 2 | 3 | 4 | 6 | 9 | 13 |


#### 3.1.b Développement / Implémentation

La représentation de l’arbre sous forme de liste Python est la suivante :

arbre = [
    "J", "D", "T", "A", "G", None, "W",
    None, None, "E", None, None, None, "U"
]
Les cases None sont utilisées lorsqu'une position ne contient pas de nœud, afin de respecter la représentation d’un arbre binaire dans une liste.

#### 3.1.c Résultats
Nombre de cases : 14
Nombre de None : 6
Parcours en largeur : J → D → T → A → G → W → E → U
Feuilles : A, E et U
Nombre de branches : 7
Nombre de niveaux : 4

Le parcours en largeur correspond à l’ordre des nœuds dans la liste lorsqu’on ignore les valeurs None.
---

### 3.3 Laura Sorro

> **Responsable : Laura Sorro**

[ESPACE RÉSERVÉ À LAURA SORRO]

#### 3.2.1 Travail réalisé

[À compléter]

#### 3.2.2 Développement / Implémentation

[À compléter]

#### 3.2.3 Résultats

[À compléter]

---


## 5. Difficultés rencontrées et solutions

[À compléter]

---

## 6. Conclusion

[À compléter]

---
