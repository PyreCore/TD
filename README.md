# TD — Travaux dirigés du DUT Informatique

Dépôt regroupant les **travaux dirigés (TD)** et **travaux pratiques (TP)** réalisés pendant la formation en DUT Informatique. Il contient deux volets distincts : des pages web de premiers pas, et des exercices de programmation en **C++**.

## Structure du dépôt

| Élément | Description |
| --- | --- |
| `index.html` | Page web du premier TP (HTML) |
| `css/` | Feuilles de style du premier TP (`style.css`, images d'illustration) |
| `js/` | Scripts JavaScript du premier TP |
| `TD_Program_C++/exo1.cpp` → `exo4.cpp` | Exercices de programmation C++ (vol. 1) |
| `text.txt` | Fichier de notes / données d'exercice |
| `LICENSE` | Licence du dépôt (MIT) |

## 1. Partie web — HTML / CSS / JavaScript

Premier TP : une page web construite en HTML avec mise en forme CSS et un peu de JavaScript.

```bash
# Ouvrir directement dans un navigateur
xdg-open index.html
```

## 2. Partie programmation — C++ (`TD_Program_C++`)

Quatre exercices progressifs de calcul et de logique en C++ (gestion de prix, remises, montants…).

```bash
# Compiler et exécuter un exercice, par exemple exo1
g++ TD_Program_C++/exo1.cpp -o TD_Program_C++/exo1
./TD_Program_C++/exo1
```

Chaque fichier `.cpp` possède son binaire pré-compilé associé (`exo1`, `exo2`, …).

## Prérequis

- Navigateur web pour la partie HTML/CSS/JS.
- Compilateur C++ (`g++`) ligne de commande pour les exercices.

## Licence

Voir le fichier [LICENSE](LICENSE) — MIT.