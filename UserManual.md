# Guide utilisateur – Startpage personnelle

## Présentation

La Startpage est une page d’accueil personnelle configurable permettant de centraliser :

- les applications métier ;
- les sites favoris ;
- les outils collaboratifs ;
- les documents importants ;
- les moteurs de recherche ;
- les notes personnelles ;
- les événements et calendriers ;
- différents widgets de consultation rapide.

Les modifications sont enregistrées automatiquement dans le navigateur.

---

## 1. Structure générale

### Barre supérieure

La barre supérieure, ou **Topbar**, reste visible pendant le défilement de la page.

Elle peut contenir :

- le logo de la Startpage ;
- le titre ;
- la date ;
- le numéro de semaine ;
- des widgets placés dans un ensemble de type **Topbar, centré** ;
- les boutons d’administration.

Le logo, le titre, l’affichage de la date et celui de la semaine peuvent être configurés en mode édition.

### Boutons disponibles

| Icône | Fonction |
|---|---|
| 🔖 | Importer les favoris du navigateur |
| 📌 | Créer ou consulter le bookmarklet |
| 📥 | Importer une sauvegarde JSON |
| 📤 | Exporter la configuration |
| ✏️ | Activer ou quitter le mode édition |
| 🌙 / ☀️ | Basculer entre les thèmes sombre et clair |

---

## 2. Mode édition

Cliquer sur **✏️** pour activer le mode édition.

Ce mode permet :

- d’ajouter des ensembles ;
- de modifier les ensembles existants ;
- d’ajouter, modifier ou supprimer des tuiles ;
- de déplacer les tuiles et les ensembles par glisser-déposer ;
- de modifier la largeur d’une tuile ;
- de définir un commentaire d’aide sur une tuile.

Un second clic sur **✏️** permet de quitter le mode édition.

---

## 3. Ensembles de tuiles

Les widgets sont organisés en **ensembles de tuiles**.

Chaque ensemble possède notamment :

- un nom ;
- un logo facultatif ;
- une taille de tuiles ;
- un type d’affichage ;
- un état replié ou déplié.

### Créer un ensemble

En mode édition, cliquer sur **＋ Nouvel ensemble de tuiles**, puis renseigner ses paramètres.

### Modifier un ensemble

Cliquer sur le bouton **✏️** de son en-tête.

### Tailles disponibles

| Taille | Usage conseillé |
|---|---|
| Très compact | Grande quantité de raccourcis |
| Compact | Applications et favoris usuels |
| Normal | Widgets nécessitant davantage d’espace |
| Large | Images et widgets riches |

Les modes à hauteur fixe permettent de conserver une grille régulière lorsque la largeur de la fenêtre change.

### Type d’ensemble

#### Standard

L’ensemble est affiché dans la zone principale de la page.

#### Topbar, centré

L’ensemble est intégré directement dans la barre supérieure. Ce mode convient particulièrement à la **Recherche globale des tuiles**.

### Replier un ensemble

Cliquer sur son chevron ou sur son titre en mode normal pour masquer temporairement les tuiles sans les supprimer.

---

## 4. Gestion des tuiles

### Ajouter une tuile

En mode édition, cliquer sur **＋** dans l’ensemble souhaité, puis sélectionner le type de widget.

### Modifier ou supprimer une tuile

- **✏️** : modifier la tuile ;
- **✕** : supprimer la tuile.

### Déplacer une tuile

En mode édition, saisir la tuile et la déposer à la position souhaitée, dans le même ensemble ou dans un autre.

### Modifier la largeur

Utiliser la poignée **⤢** placée en bas à droite de la tuile. Une tuile peut occuper plusieurs colonnes. Son étendue est ajustée au nombre de colonnes disponibles lorsque la fenêtre change de taille.

---

## 5. Commentaires au survol

Chaque tuile peut posséder un commentaire personnalisé.

En mode édition, ouvrir la configuration de la tuile et renseigner **Commentaire affiché au survol de la tuile**.

En mode normal, placer la souris sur la tuile. Après un court délai, une infobulle apparaît près du curseur.

L’infobulle :

- accepte plusieurs lignes ;
- suit le curseur ;
- se repositionne près des bords de l’écran ;
- disparaît lorsque la souris quitte la tuile ;
- n’est pas affichée en mode édition.

---

## 6. Widgets disponibles

### Lien

Crée un raccourci vers un site Web.

Paramètres disponibles :

- titre ;
- URL ;
- ouverture dans une nouvelle fenêtre ;
- favicon automatique ;
- image personnalisée ;
- emoji ou icône.

### Recherche multi-moteurs

Une même tuile peut contenir plusieurs moteurs de recherche, disposés verticalement. Chaque moteur possède son propre champ et son bouton **→**.

Exemple :

```text
Google       [ Rechercher… ] [→]
Ecosia       [ Rechercher… ] [→]
Wikipédia    [ Rechercher… ] [→]
```

Pour lancer une recherche :

- saisir le texte sur la ligne du moteur voulu ;
- appuyer sur `Entrée` ou cliquer sur **→**.

#### Moteurs disponibles par défaut

- DuckDuckGo ;
- Google ;
- Bing ;
- Ecosia ;
- Wikipédia ;
- YouTube.

Les moteurs intégrés ne peuvent pas être supprimés du catalogue global.

#### Configuration propre à chaque tuile

En mode édition, il est possible de :

- sélectionner les moteurs affichés ;
- désélectionner les moteurs inutiles ;
- modifier leur ordre avec **↑** et **↓** ;
- choisir si les résultats s’ouvrent dans un nouvel onglet.

Chaque tuile possède sa propre sélection et son propre ordre.

#### Ajouter un moteur personnalisé

Dans la configuration d’une tuile Recherche, renseigner :

- son nom ;
- son URL de requête.

Format recommandé :

```text
https://monmoteur.com/search?q={query}
```

Le marqueur `{query}` est remplacé par le texte recherché. S’il est absent, la Startpage ajoute automatiquement un paramètre `q={query}`.

Un moteur personnalisé est ajouté au catalogue global et devient disponible pour toutes les tuiles Recherche. Sa suppression le retire également des tuiles qui l’utilisent.

### Recherche globale des tuiles

Ce widget recherche dans les titres, types et contenus textuels des tuiles.

La recherche :

- est instantanée ;
- ignore la casse et les accents ;
- masque les tuiles sans correspondance ;
- masque les ensembles sans résultat ;
- indique le nombre de résultats.

Le bouton **×** efface le filtre. La position recommandée est la Topbar.

### Horloge

Le widget peut afficher :

- le numéro de semaine ;
- la date ;
- l’heure ;
- éventuellement les secondes.

Un lien facultatif peut lui être associé.

### Note

Le widget Note affiche un titre facultatif et un contenu texte.

En mode normal, cliquer sur la note ouvre un éditeur agrandi utilisant environ 75 % de la largeur de l’écran.

L’éditeur permet de modifier :

- le titre ;
- le contenu.

Commandes disponibles :

- **Enregistrer** : sauvegarder ;
- **Annuler** : fermer sans enregistrer ;
- `Ctrl + Entrée` : enregistrer rapidement ;
- `Échap` : fermer la fenêtre.

La modale ne se ferme pas lorsqu’un clic commence à l’intérieur et se termine à l’extérieur.

### Agenda

Chaque ligne suit ce format :

```text
AAAA-MM-JJ | HH:MM | Titre
```

Exemple :

```text
2026-11-12 | 14:00 | Rendez-vous
```

L’heure peut être omise :

```text
2026-11-15 | | Anniversaire
```

Les événements sont triés par date.

### Image

Affiche une image dans une tuile. Un lien facultatif peut rendre l’image cliquable.

---

## 7. Calendrier

Cliquer sur la date ou le numéro de semaine sous le titre pour ouvrir le calendrier.

### Vue Mois

La vue Mois affiche six semaines complètes avec :

- le numéro ISO de chaque semaine ;
- les colonnes du lundi au dimanche ;
- la mise en évidence du jour courant.

Navigation :

- **‹** et **›** : période précédente ou suivante ;
- **↑ 1 sem.** et **↓ 1 sem.** : décaler l’affichage d’une semaine ;
- molette de la souris dans le calendrier : déplacement semaine par semaine ;
- **Aujourd’hui** : revenir à la période courante.

### Vue Semaine

Cliquer sur **Semaine** pour afficher une seule semaine. Dans ce mode, **‹** et **›** passent à la semaine précédente ou suivante.

---

## 8. Jours fériés et vacances scolaires

### Jours fériés

L’option **Jours fériés officiels** affiche les jours fériés de France métropolitaine. Ils apparaissent en rouge.

### Vacances scolaires

Activer **Vacances scolaires**, puis sélectionner :

- Zone A ;
- Zone B ;
- Zone C ;
- Corse.

Les vacances apparaissent en orange. Une liste de sources proposées permet de charger les jours fériés ou les vacances d’une zone.

---

## 9. Calendriers ICS / iCal

Des événements personnels peuvent être importés depuis un calendrier ICS/iCal.

### Depuis une URL

Renseigner l’adresse du calendrier, puis cliquer sur **Charger l’URL**.

Certains serveurs bloquent le chargement direct depuis une page Web. Dans ce cas, utiliser l’import de fichier.

### Depuis un fichier

Cliquer sur **Importer un fichier**. Les formats `.ics` et `.ical` sont acceptés.

Les événements sont affichés en vert et conservés localement. Les imports successifs sont regroupés en utilisant l’identifiant iCal lorsque celui-ci est disponible.

---

## 10. Événements personnels

Cliquer sur **＋ Ajouter un événement**, puis renseigner :

- le titre ;
- la date et l’heure de début ;
- la date et l’heure de fin ;
- une description facultative.

Un bouton **×** permet de supprimer individuellement un événement personnel.

Le bouton **Effacer les événements** supprime l’ensemble des événements personnels. Les jours fériés et vacances scolaires ne sont pas concernés.

---

## 11. Import des favoris

Cliquer sur **🔖**.

Une page Web ne pouvant pas lire directement les favoris du navigateur, il faut d’abord les exporter au format HTML.

### Chrome et Edge

Ouvrir le gestionnaire de favoris, par exemple avec `Ctrl + Shift + O`, puis utiliser la fonction d’export.

### Firefox

Utiliser l’export HTML des marque-pages.

### Import dans la Startpage

Après sélection du fichier :

1. parcourir l’arborescence ;
2. cocher les favoris ou dossiers souhaités ;
3. choisir la destination ;
4. choisir éventuellement l’utilisation des favicons ;
5. lancer l’import.

Les favoris peuvent être ajoutés à un ensemble existant, à un nouvel ensemble ou à un ensemble créé pour chaque dossier sélectionné.

---

## 12. Ajout rapide d’un favori

Utiliser `Ctrl + D` sur la Startpage, ou `Cmd + D` sur macOS.

Le formulaire permet de renseigner :

- l’URL ;
- le titre ;
- l’ensemble de destination ;
- l’ouverture dans une nouvelle fenêtre ;
- la favicon ;
- une image ;
- un emoji.

Le champ URL accepte également :

```text
Titre | URL
```

Exemple :

```text
Microsoft Copilot | https://copilot.microsoft.com
```

---

## 13. Bookmarklet

Cliquer sur **📌** en mode édition, puis glisser **Ajouter à ma startpage** dans la barre de favoris du navigateur.

Depuis un site Web, cliquer sur ce favori pour ouvrir la Startpage avec le titre et l’URL préremplis.

Si l’ouverture automatique est bloquée, le bookmarklet tente de copier `Titre | URL` dans le presse-papiers.

---

## 14. Sauvegarde de la configuration

### Exporter

En mode édition, cliquer sur **📤**. Un fichier `startpage-config.json` est téléchargé.

Il contient notamment :

- les ensembles ;
- les tuiles ;
- leur configuration ;
- les commentaires au survol ;
- le catalogue des moteurs personnalisés ;
- les paramètres généraux.

### Importer

Cliquer sur **📥**, puis sélectionner un export JSON précédent. La configuration importée remplace la configuration active.

> Conseil : effectuer un export avant toute modification importante.

---

## 15. Stockage des données

La configuration principale est enregistrée localement dans le navigateur sous la clé `startpage.v1`.

Le calendrier utilise une zone distincte, `startpage.calendar.v1`, pour conserver notamment :

- ses réglages ;
- la zone scolaire ;
- les événements personnels.

Les données sont donc liées au navigateur et au profil utilisateur. L’export JSON est recommandé pour les sauvegarder ou les transférer.

---

## 16. Thèmes

Deux thèmes sont disponibles :

- 🌙 **mode sombre** ;
- ☀️ **mode clair**.

Le changement s’effectue depuis la Topbar.

---

## 17. Raccourcis utiles

| Action | Raccourci |
|---|---|
| Ajouter rapidement un favori | `Ctrl + D` ou `Cmd + D` |
| Enregistrer une note ouverte | `Ctrl + Entrée` |
| Fermer l’éditeur de note | `Échap` |
| Ouvrir le calendrier au clavier | `Entrée` ou `Espace` lorsque la date est sélectionnée |

---

## 18. Bonnes pratiques

- Utiliser **Très compact** pour les ensembles comportant beaucoup de raccourcis.
- Utiliser **Compact** pour les applications utilisées régulièrement.
- Utiliser **Normal** lorsque le contenu nécessite davantage de hauteur.
- Utiliser **Large** pour les éléments visuels ou les widgets riches.
- Placer la **Recherche globale** dans la Topbar.
- Utiliser les commentaires au survol pour documenter les applications ou rappeler une procédure.
- Créer plusieurs tuiles Recherche spécialisées au lieu d’une seule contenant tous les moteurs.
- Effectuer régulièrement un export JSON.
- Importer les calendriers ICS par fichier lorsque leur serveur interdit l’accès direct depuis le navigateur.

---
Manuel utilisateur généré par MS Copilot