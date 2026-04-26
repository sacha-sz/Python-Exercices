# 🐍 INF2 - Travaux Pratiques & Dirigés en Python

Ce dépôt regroupe l'ensemble des codes sources réalisés dans le cadre de l'UV **INF2** à l'UTC, dédiée à la **programmation orientée objet et aux structures de données en Python**.

Les programmes sont écrits en **Python**, organisés par **TD** et **TP** dans des dossiers indépendants. Les rendus des TP sont au format **Jupyter Notebook** et peuvent être visualisés directement sur GitHub ou exécutés localement.

<br/>

## 📌 Vue d'ensemble

### Travaux Dirigés (TD)

| TD | Thème principal | Dossier |
|----|----------------|---------|
| TD01 | Structures de contrôle : boucles imbriquées, affichages de motifs | [`TD/TD01/`](TD/TD01/) |
| TD02 | Récursivité : suite de Fibonacci, fonctions récursives | [`TD/TD02/`](TD/TD02/) |
| TD03 | Programmation orientée objet : classes, encapsulation, getters/setters | [`TD/TD03/`](TD/TD03/) |
| TD04 | Structures de données : graphes, sommets, arêtes | [`TD/TD04/`](TD/TD04/) |
| TD05 | POO avancée : héritage, propriétés, manipulation d'images (PIL) | [`TD/TD05/`](TD/TD05/) |
| TD06 | Structures de données : piles, files, vérification de parenthèses | [`TD/TD06/`](TD/TD06/) |
| TD07 | Fichiers et NumPy : lecture/écriture, courbes, données CSV | [`TD/TD07/`](TD/TD07/) |
| TD08 | Interfaces graphiques avec Tkinter | [`TD/TD08/`](TD/TD08/) |
| TD09 | Bases de données relationnelles avec SQLite | [`TD/TD09/`](TD/TD09/) |
| TD11 | Application web Django : modèles, vues, formulaires, templates | [`TD/TD11/`](TD/TD11/) |
| TD12 | Calcul matriciel et visualisation avec NumPy | [`TD/TD12/`](TD/TD12/) |

### Travaux Pratiques (TP)

| TP | Thème principal | Dossier |
|----|----------------|---------|
| TP1 | Introduction à Python : bases de la programmation, corrections fournies | [`TP/TP1/`](TP/TP1/) |
| TP2 | Récursivité : palindromes, chiffrement de César, évaluation de mots de passe | [`TP/TP2/`](TP/TP2/) |
| TP3 | Géolocalisation et POO : coordonnées GPS via Google Maps API | [`TP/TP3/`](TP/TP3/) |
| TP4 | Fichiers et Matplotlib : lecture de données, tracé de courbes et formes | [`TP/TP4/`](TP/TP4/) |
| TP5 | Interface graphique Tkinter : calculatrice avec gestion d'erreurs | [`TP/TP5/`](TP/TP5/) |
| TP6 | Application web Django : authentification, profils, simulations | [`TP/TP6/`](TP/TP6/) |

<br/>

## 🗂 Détail des exercices

### TD01 - Structures de contrôle

| Fichier | Contenu |
|---------|---------|
| `TD1-1.py` | Affichage de pyramides de chiffres avec des boucles imbriquées |
| `TD1-1-Alternatif.py` | Variante de la pyramide avec une approche alternative |
| `TD1-2.py` à `TD1-8-Final.py` | Exercices progressifs sur les boucles et structures de contrôle |

---

### TD02 - Récursivité

| Fichier | Contenu |
|---------|---------|
| `TD2-1.py` | Suite de Fibonacci : calcul récursif et affichage jusqu'à une limite |
| `TD2-2.py` | Autres fonctions récursives classiques |
| `TD2-3.py` / `TD2-3-alternatif.py` / `TD2-3-suite.py` | Exercice avancé de récursivité avec variantes |

---

### TD03 - Programmation orientée objet

| Fichier | Contenu |
|---------|---------|
| `TD3-1.py` | Classe `Date` : encapsulation, getters/setters, validation des jours par mois |
| `TD3-1-correction.py` | Correction commentée de l'exercice 1 |
| `TD3-2.py` | Classe avec héritage et redéfinition de méthodes |
| `TD3-2-correction.py` | Correction commentée de l'exercice 2 |

---

### TD04 - Structures de données : graphes

| Fichier | Contenu |
|---------|---------|
| `TD4-1.py` | Classe `Sommet` : identifiant, encapsulation, comptage des instances |
| `TD4-1.1.py` | Extension de la classe `Sommet` |
| `TD4-2.py` | Classe `Graphe` : gestion des arêtes et parcours |
| `Revision.py` | Exercices de révision sur les structures de données |

---

### TD05 - POO avancée

| Fichier | Contenu |
|---------|---------|
| `MyNotes.py` | Classe `Note` avec propriétés Python, héritage et manipulation d'images via PIL |

---

### TD06 - Piles et files

| Fichier | Contenu |
|---------|---------|
| `TD6-1.py` | Vérification de parenthèses équilibrées avec une pile (`collections.deque`) |
| `TD6-2.py` | Implémentation et manipulation d'une file |
| `TD6-3.py` | Exercice avancé sur les structures LIFO/FIFO |

---

### TD07 - Fichiers et NumPy

| Fichier | Contenu |
|---------|---------|
| `EX1.py` | Génération de fichiers de valeurs mathématiques (sinus, distances) avec NumPy |
| `EX2.py` | Lecture et traitement de fichiers CSV de notes |
| `EX3.py` | Analyse de données CO₂ (`co2-annmean-mlo.csv`) |
| `affichage_graphique.py` | Module utilitaire de tracé graphique partagé |

---

### TD08 - Interfaces graphiques Tkinter

| Fichier | Contenu |
|---------|---------|
| `EX1.py` | Fenêtre Tkinter centrée, dimensionnement dynamique |
| `EX2.py` | Widgets interactifs : boutons, labels, champs de saisie |
| `EX3.py` | Canvas et dessin de formes géométriques |
| `EX4.py` | Application graphique complète multi-composants |

---

### TD09 - Bases de données SQLite

| Fichier | Contenu |
|---------|---------|
| `EX1.py` | Connexion SQLite, exécution de requêtes SQL, affichage des résultats |

---

### TD11 - Application web Django

Application Django complète de **gestion de cours** :

| Composant | Contenu |
|-----------|---------|
| `gestion_cours/models.py` | Modèles `Bureau`, `Intervenant`, `Cours` avec contraintes d'unicité |
| `gestion_cours/views.py` | Vues CRUD pour les cours et intervenants |
| `gestion_cours/forms.py` | Formulaires Django associés |
| `gestion_cours/templates/` | Templates HTML : base, création de cours, structure |
| `manage.py` | Point d'entrée de l'application Django |

---

### TD12 - Calcul matriciel et visualisation

| Fichier | Contenu |
|---------|---------|
| `EX1.py` | Génération de matrices aléatoires avec colonne biais (NumPy) |
| `EX2.py` | Opérations matricielles et visualisation |
| `EX3.py` | Exercice de calcul et affichage graphique |

---

### TP1 - Introduction à Python

Exercices fondamentaux avec corrections fournies :

| Dossier | Contenu |
|---------|---------|
| `TP1/TP1.ipynb` | Notebook principal du TP1 |
| `Corrections TP1/ex1.py` à `ex6.py` | Corrections officielles des 6 exercices |

---

### TP2 - Récursivité et manipulation de chaînes

| Exercice | Contenu |
|----------|---------|
| Q1 | Fonction récursive `ispalindrome` - vérification de palindromes |
| Q2 | Chiffrement de César - décalage alphabétique avec `crypter` |
| Q3 | Évaluation de la force d'un mot de passe (score pondéré) |

> 📓 Notebook : [`TP2 - INF2.ipynb`](TP/TP2/TP2%20-%20INF2.ipynb)

---

### TP3 - Géolocalisation et POO

| Exercice | Contenu |
|----------|---------|
| EX1 | Classe `Lieu` avec récupération automatique des coordonnées GPS via Google Maps API |
| EX2 | Calcul de distances entre lieux et affichage carte |

> 📓 Notebook : [`TP3 - INF2.ipynb`](TP/TP3/TP3%20-%20INF2.ipynb)

---

### TP4 - Fichiers et Matplotlib

| Exercice | Contenu |
|----------|---------|
| Fichiers texte | Lecture de `admis.txt` / `concours.txt`, traitement de données de concours |
| Fichiers CSV | Analyse de `math.csv` / `math2.csv` avec statistiques descriptives |
| Matplotlib | Tracé de courbes cosinus et cercles colorés |

> 📓 Notebook : [`TP4 - INF2.ipynb`](TP/TP4/TP4%20-%20INF2.ipynb)

---

### TP5 - Interface graphique : Calculatrice Tkinter

Implémentation d'une **calculatrice graphique** gérant :
- Opérations de base (+, −, ×, ÷) et fonctions mathématiques (sin, cos, tan, √, puissance)
- Gestion robuste des erreurs : division par zéro, syntaxe invalide, valeurs incorrectes

> 📓 Notebook : [`TP5 - INF2.ipynb`](TP/TP5/TP5%20-%20INF2.ipynb)

---

### TP6 - Application web Django : gestionnaire de simulations

Application Django complète avec authentification et gestion de profils utilisateurs :

| Composant | Contenu |
|-----------|---------|
| `sim_manager/models.py` | Modèles de données pour les simulations |
| `sim_manager/views.py` | Vues : création de simulation, liste, partage, profil utilisateur |
| `templates/` | Templates : connexion, profil, nouvelle simulation, graphiques |
| `manage.py` | Point d'entrée Django |

> 📓 Notebook : [`TP6 - INF2.ipynb`](TP/TP6/TP6%20-%20INF2.ipynb)

<br/>

## 🛠 Exécution

### Prérequis

```bash
pip install jupyter numpy matplotlib pillow googlemaps django
```

### Lancer les TP (Jupyter Notebook)

```bash
# Ouvrir un TP directement
jupyter notebook "TP/TP2/TP2 - INF2.ipynb"

# Ou lancer Jupyter depuis la racine du projet
jupyter notebook
```

### Lancer les TD (scripts Python)

```bash
# Exemple TD02 - Fibonacci
python TD/TD02/TD2-1.py

# Exemple TD08 - Interface graphique
python TD/TD08/EX1.py
```

### Lancer les applications Django (TD11 / TP6)

```bash
# TD11 - Gestion de cours
cd TD/TD11
python manage.py runserver

# TP6 - Gestionnaire de simulations
cd TP/TP6/TP6-INF2
python manage.py runserver
```

<br/>

## 🧰 Technologies utilisées

- **Python 3** - [python.org](https://www.python.org/)
- **Jupyter Notebook** - environnement interactif pour les TP
- **NumPy / Matplotlib** - calcul numérique et visualisation (TD07, TD12, TP4)
- **Tkinter** - interfaces graphiques (TD08, TP5)
- **SQLite** - bases de données relationnelles (TD09)
- **Django** - framework web Python (TD11, TP6)
- **PIL / Pillow** - manipulation d'images (TD05)

<br/>

## 📄 Licence

Ce projet est distribué sous licence **MIT** - voir le fichier [LICENSE](LICENSE) pour plus d'informations.

<br/>

## 👤 Auteur

- **[@sacha-sz](https://github.com/sacha-sz)**

<br/>

## 🔗 Références

- [🔒 Cours INF2 sur Moodle (accès UTC requis)](https://moodle.utc.fr/course/view.php?id=2590)
- [UTC - Université de Technologie de Compiègne](https://www.utc.fr/)

