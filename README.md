# Projet 2 - Word Press (par Mohamed, Yana et Ziadoon)

Le client est un label de musique Liégeois portant le nom du **Wi m'fi Records**. Leur mission principale est de produire, d'éditer, de distribuer les artistes locaux. Ils mettent en lumière les albums (numériques, disques et vinyles), les news et les évenements, mais également un e-shop avec la possibilité d'obtenir les albums, ainsi que des produits dérivés.

Le projet s'articule en **trois grandes fonctionnalités** :

* Une page d'acceuil à intégrer en fonction des éléments déjà présents ;

* La mise en lumière des évenements, news, artistes via un système d'articles ;

* Un e-shop permettant la mise en vente des albums numériques, disques et vinyle ainsi que les produits dérivés : t-shirts, stickers, affiches.

## Fonctionalités demandées

### ADMINS (Super-utilisateurs)

* Gérer, supprimer et ajouter des articles/news ;
* Gérer, supprimer et ajouter des items à vendre dans le e-shop ;
* Gérer, supprimer et ajouter des évenements ;
* Choisir quels évenements vont être affichés sur la page d'accueil ;
* Gérer, supprimer et ajouter des albums à la colonne (section) **Discographie** (pages *About* et *Blog*).

#### Onglets WordPress

* Articles/news ;
* Evenements ;
* Discographie ;
* E-shop - Musiques ;
* E-shop - Produits dérivés.

### Page d'accueil

* Header ;
* Bannière ;
* "Mots du label" ;
* "Prochains évenements" (choisis par un **Admin**) - vignettes, 4, avec slides pour plus ;
* "Pourquoi nous ?", 3 ;
* Footer.

### Page About

* Header ;
* "Notre histoire" ;
* Section (colonne) **Discographie** - créée avec le **plug-in ACF**, gerée par le **Admin** ;
* Footer.

### Page Galerie

* Header ;
* "Galerie" - Système de filtration ("Tout", "Concerts", "Groupes", "Stuff") + photos (4 par lignes) ;
* Footer.

### Page E-shop (albums / produits dérivés)

* Header ;
* Deux sections distinctes - **Acheter la Musique** et **Produits dérivés** avec 4 items chacun ;
* Footer.

:bulb: Le systeme d'e-shop - **WooCommerce** avec le payement via bancontact/mastercard ou via virement bancaire (à voir selon les **plugins** mis à disposition).

### Page Blog/News

* Header ;
* Les news/articles du label sous forme de vignettes - 5, date, image, titre, extrait de l'article + **button** redirigeant vers l'article détaillé ;
* Section (colonne) **Discographie** - créée avec le **plug-in ACF**, gerée par le **Admin** ;
* Footer.

#### Une news

* Header ;
* L'article détaillé de la news (image + date + titre + texte) ;
* Footer.

### Page Contact

* Header ;
* Formulaire (inputs de nom, e-mail, website/objet/thème et texte) de contact - système de messagerie (avec un **plug-in au choix**) - pour artistes qui veulent contacter le label ;
* Google Map ;
* Footer.

### Bonus

[] Intégration des **vidéos** clips dans les articles (News, par exemple) ;
[] Diffuser en bas les produits dérivés d'un album précis, lorsque nous sommes sur la page de cet album ;
[] Rendre le design (style) plus **Punk** ;
[] L'article détaillé d'un évenement ;
[] Le système des filtres/tags pour les news et évenements ;
[] Le système de filtration pour les photos, sur la page Galerie.

## Découpe du template

### Header (navigation)

* Logo et slogan ;
* Lien Accueil ;
* Lien Galerie ;
* Lien Shop ;
* Lien Blog ;
* Lien Contact.

### Footer

* Logo ;
* Adresse ;
* Mail ;
* S'inscrire à la newsletter avec un input pour le mail et un button submit ;
* 4 pictos/liens vers les réseaux sociaux ;
* Copyright.

### Bannière - Best news

3 slides avec Titre, sous-titre (lieu, date ?), courte description, button "Lire plus".

### Section "Mots du label"

2 slides avec Citation, author, sa fonction.

### Section "Prochains évenements"

4 évenements avec Date, titre et courte description.

### Section "Pourquoi nous ?"

3 raisons avec Image, nom, courte description.

### Section "Notre histoire"

Titre, image, intro, texte.

### Colonne Discographie

5 vignettes avec Image, titre, année, le nombre des morceaux.

### Section "Galerie

* Système de filtration - "Tout", "Concerts", "Groupes", "Stuff" - bonus ;
* Les photos, 4 par lignes.

### Article (la vignette)

* Date ;
* Image ;
* Titre ;
* Extrait de l'article ;
* Button Lire plus.

### Un item dans e-shop 

* Nom ;
* Année ;
* Button **Acheter** ;
* Button **Écouter** pour écouter l'album ou **Regarder** pour afficher une image du produit dérivé ;
* Section de Partage - 4 pictos/liens vers les réseaux sociaux, pour partager l'achat.

## Le travail de groupe

### Disponibilités

| Dates        | Mohamed    | Yana       | Ziadoon    |
| ------------ | ---------- | ---------- | ---------- |
| LU **14/9**  | v          | v          | v          |
| MA **15/9**  | v          | v          | v          |
| ME **16/9**  | v          | v          | v          |
| JE **17/9**  | v          | v          | v          |
| VE **18/9**  | v          | v          | v          |
| **WEEK-END** | **x**      | **x**      | **x**      |
| LU **21/9**  | v          | v          | v          |
| MA **22/9**  | v          | v          | v          |
| ME **23/9**  | v          | v          | v          |
| JE **24/9**  | v          | v          | v          |
| VE **25/9**  | **CEFORA** | **CEFORA** | **CEFORA** |
| **WEEK-END** | **x**      | **x**      | **x**      |
| LU **28/9**  | v          | v          | v          |
| MA **29/9**  | v          | v          | v          |
| ME **30/9**  | v          | v          | v          |
| JE **1/10**  | v          | v          | v          |
| VE **2/10**  | **CEFORA** | **CEFORA** | **CEFORA** |

### Deadlines

:bulb: **Stand up meeting chaque matin**

**18/9** Lire le pdf, créer un fichier avec des questions, faire réunion commune penchant sur les questions ;
**30/9** Mise en commun du travail de chaque personne ;
**1/10** Correction, si nécessaire, le rendu du projet.

### Trello

### Recherches / à faire rapidement

* Comment génerer une page détaillée d'un article/news ;
* Faire table de matière - read me ;
* Comment faire un lien direct dans le read me.
