Voici un fichier `README.md` prêt à l’emploi pour ton projet **PUZZLE-15** en Haskell :

---

```markdown
# 🧩 Puzzle-15 Terminal - Haskell

Ce projet est une version en ligne de commande du célèbre **jeu du taquin** (aussi appelé *Puzzle-15*), codée en **Haskell**.

---

## 🎮 Objectif du jeu

Le but est de **reconstituer une grille 4×4** contenant les nombres de **1 à 15** dans l’ordre, en déplaçant les tuiles pour replacer la case vide (`0`) dans la bonne position.

```

1  2  3  4
5  6  7  8
9 10 11 12
13 14 15 0

````

---

## 🚀 Lancer le jeu

### 1. Compiler le code

```bash
ghc puzzle15.hs -o puzzle15
````

### 2. Exécuter le jeu

```bash
./puzzle15
```

> Si `ghc` n'est pas installé, installe GHC via [`ghcup`](https://www.haskell.org/ghcup/).

---

## 🕹️ Contrôles

* `w` : Haut
* `s` : Bas
* `a` : Gauche
* `d` : Droite
* `q` : Quitter le jeu

---

## ✨ Fonctionnalités

* Mélange **aléatoire et toujours solvable**
* Affichage **graphique en terminal** (avec couleurs)
* Compteur de coups
* Vérification automatique de victoire
* Code simple et lisible pour étude pédagogique

---

## 📁 Structure

* `puzzle15.hs` : code source principal
* `README.md` : ce fichier de documentation

---

## 🧠 Concepts Haskell utilisés

* Types personnalisés (`type Board`)
* IO monad (`IO Board`, `getLine`, `putStrLn`, etc.)
* Recursion et expressions de liste
* Mélange aléatoire avec `System.Random`

---

## 📜 Licence

Ce projet est distribué librement pour l’apprentissage.
Tu peux le modifier, l'étendre ou l’utiliser comme base pour créer un jeu graphique.

---

## ✍️ Auteur

Konan Yable Yves Charlain
---
