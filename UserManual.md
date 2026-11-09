# Guide Utilisateur – Startpage Personnelle

## Présentation

Cette startpage est une page d’accueil personnelle et entièrement configurable permettant de centraliser :

- Les applications métier
- Les sites favoris
- Les outils collaboratifs
- Les documents importants
- Les widgets de consultation rapide

Toutes les modifications sont enregistrées automatiquement dans le navigateur.

---

# Structure générale

La page est composée de :

## Barre supérieure (Topbar)

La topbar reste visible pendant le défilement.

Elle contient :

- Le logo de la startpage
- Le titre de la startpage
- La date et/ou la semaine en cours
- Les widgets de topbar
- Les boutons d'administration

### Boutons disponibles

| Icône | Fonction |
|---------|----------|
| 🔖 | Import de favoris navigateur |
| 📌 | Création du bookmarklet |
| 📥 | Import d'une sauvegarde |
| 📤 | Export d'une sauvegarde |
| ✏️ | Activer le mode édition |
| 🌙 / ☀️ | Changer le thème |

---

# Mode édition

Le mode édition permet de modifier entièrement la page.

Activation :

```text
✏️
```

Une fois activé, il devient possible :

- d'ajouter des ensembles
- d'ajouter des tuiles
- de déplacer les ensembles
- de déplacer les tuiles
- de supprimer des éléments
- de redimensionner certaines tuiles

---

# Les ensembles de tuiles

Les tuiles sont regroupées dans des ensembles.

Chaque ensemble possède :

- un nom
- un logo optionnel
- une taille d'affichage
- un type d'affichage

---

## Créer un ensemble

Cliquer sur :

```text
+ Nouvel ensemble de tuiles
```

Puis renseigner :

- Nom
- Logo
- Taille
- Type

---

## Modifier un ensemble

Cliquer sur :

```text
✏️ Renommer l'ensemble
```

Les paramètres suivants sont disponibles.

---

### Nom

Titre affiché dans l'en-tête du groupe.

---

### Logo

Formats acceptés :

- PNG
- JPG
- SVG

---

### Taille des tuiles

#### Très compact

Affichage extrêmement dense.

Utilisation recommandée :

```text
Favoris nombreux
Applications métiers
```

---

#### Compact

Affichage dense.

Utilisation recommandée :

```text
Applications utilisées quotidiennement
```

---

#### Normal

Taille standard.

Utilisation recommandée :

```text
Widgets
Agenda
Notes
```

---

#### Large

Affichage confortable.

Utilisation recommandée :

```text
Météo
Images
Tableaux de bord
```

---

## Type d'ensemble

### Standard

Affichage normal dans la page.

---

### Topbar, centré

Le groupe est affiché directement dans la barre supérieure.

Exemples :

- Recherche globale
- Widget météo
- Informations système
- Horloge

---

## Largeur du groupe Topbar

Exemple :

```text
620
```

Permet de fixer la largeur du groupe lorsqu'il est intégré dans la topbar.

---

# Gestion des tuiles

## Ajouter une tuile

Cliquer sur :

```text
+
```

dans l'ensemble souhaité.

---

## Modifier une tuile

Cliquer sur :

```text
✏️
```

sur la tuile concernée.

---

## Supprimer une tuile

Cliquer sur :

```text
✕
```

sur la tuile concernée.

---

## Déplacer une tuile

En mode édition :

- glisser la tuile
- déposer dans un autre groupe ou à une autre position

---

## Redimensionner une tuile

Utiliser la poignée :

```text
⤢
```

située en bas à droite.

Elle permet d'étendre la tuile sur plusieurs colonnes.

---

# Widgets disponibles

---

## Lien

Création d'un raccourci vers un site web.

Paramètres :

- titre
- URL
- favicon automatique
- image personnalisée
- emoji

Exemple :

```text
Titre : GitHub
URL : https://github.com
```

---

## Recherche

Moteurs disponibles :

- Google
- DuckDuckGo
- Bing
- Wikipédia
- YouTube

---

## Recherche globale

Recherche simultanément dans toutes les tuiles de la startpage.

Fonctionnalités :

- recherche instantanée
- ignore les accents
- filtre automatiquement les résultats
- affiche le nombre de correspondances

Position recommandée :

```text
Topbar
```

---

## Horloge

Affiche :

- date
- semaine
- heure

Options :

```text
Avec ou sans secondes
```

---

## Agenda

Format :

```text
2026-10-15 | 09:00 | Réunion d'équipe
2026-11-01 |       | Congés
```

---

## Note

Bloc texte libre.

Exemples :

```text
Todo
Procédure
Liste de courses
Notes de réunion
```

---

## Image

Affiche :

- image
- logo
- bannière

Lien cliquable possible.

---

# Recherche globale

Ajouter le widget :

```text
Recherche globale des tuiles
```

Puis saisir un mot-clé.

Exemples :

```text
gitlab
```

```text
documentation
```

La page masque automatiquement :

- les tuiles non correspondantes
- les groupes sans résultat

---

# Import de favoris navigateur

Cliquer sur :

```text
🔖
```

---

## Export depuis Chrome / Edge

```text
Ctrl + Shift + O
```

Puis :

```text
Exporter les favoris
```

---

## Export depuis Firefox

```text
Bibliothèque
→ Marque-pages
→ Exporter les marque-pages au format HTML
```

---

## Import dans la startpage

Après sélection du fichier :

- cocher les favoris souhaités
- choisir la destination

Options disponibles :

### Ajouter dans un groupe existant

Les favoris sont ajoutés dans un groupe choisi.

---

### Nouvel ensemble

Création automatique d'un groupe.

---

### Un ensemble par dossier

Création d'un groupe pour chaque dossier importé.

---

# Ajout rapide de favoris

## Depuis la startpage

Raccourci clavier :

```text
Ctrl + D
```

Ouvre directement le formulaire d'ajout.

---

# Bookmarklet

Cliquer sur :

```text
📌
```

Puis glisser le lien proposé dans la barre de favoris du navigateur.

Depuis n'importe quel site :

```text
Ajouter à ma startpage
```

ouvrira le formulaire pré-rempli avec :

- le titre de la page
- l'URL

---

# Sauvegarde

## Export

Cliquer sur :

```text
📤
```

Un fichier :

```text
startpage-config.json
```

est téléchargé.

---

## Import

Cliquer sur :

```text
📥
```

Puis sélectionner une sauvegarde précédente.

---

# Thèmes

## Mode sombre

```text
🌙
```

Thème recommandé.

---

## Mode clair

```text
☀️
```

Thème lumineux.

---

# Recommandation d'organisation

```text
Topbar
 └ Recherche globale

Projet
 ├ Documentation
 ├ Référentiels
 └ Outils

IA
 ├ Copilot
 ├ ChatGPT
 ├ Mistral
 └ Claude

Personnel
 ├ Banque
 ├ Voyages
 └ Maison
```

---

# Bonnes pratiques

### Très compact

À utiliser pour :

```text
100+ favoris
```

---

### Compact

À utiliser pour :

```text
Applications métier
```

---

### Normal

À utiliser pour :

```text
Agenda
Notes
Recherche
```

---

### Large

À utiliser pour :

```text
Images
Widgets riches
Tableaux de bord
```

---
Manuel utilisateur généré par Copilot Writing Coach