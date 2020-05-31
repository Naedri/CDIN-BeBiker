# CDIN-BeBiker
IUT Paris Descartes - 2019 - Enseignant : PEROIS Cyrille.

## Projet Conception de Documents et d'Interfaces Numériques

Dans le cadre du cours de CDIN, Cyrille Perois a proposé de développer le site web d'une entreprise fictive : Be Biker Service. 

**Une version en ligne du site est disponible à l'adresse suivante : <https://cdin-bebiker-three-omega.now.sh>.**

## Auteurs

BERTHIER Nicolas : <nicolas-berthier@orange.fr>  
ESCOFFIER Vincent : <alainvincentesc@gmail.com>  
JALLAIS Adrien : <adrien.jallais@protonmail.com>  

## Briefing

Cette entreprise est spécialisée dans la réparation, le conseil et la vente d'équipements autour du vélo. C'est une entreprise locale qui existe depuis 1990, mais dont la présence en ligne est réduite à une page Facebook sur laquelle les deux co-fondateurs postent de temps en temps. Afin de se faire un peu plus connaître, l'entreprise souhaite avoir son site web presentant son activité, son univers et sa passion du vélo.

Pour cela, elle a fait appel à vous, jeune agence web, pour que vous les accompagniez dans la conception de ce site web. Le pôle design a conçu des maquettes. Votre rôle, en tant qu'intégrateur(rice)s, est maintenant de donner vie à ces maquettes et de développer le site web correspondant.

Le site web est composé de 3 pages :

* Une page d'accueil, qui présente succintement l'univers de l'entreprise et ses différents services
* Une page « Qui sommes nous ? », qui présente plus en détails l'entreprise
* Une page « Services », qui présente plus en détails les services proposés par l'entreprise

Vous trouverez les maquettes (formats desktop, tablette et mobile) dans le dossier [maquettes](https://github.com/Naedri/CDIN-BeBiker/tree/master/NOTICE/maquettes).

L'ensemble des images utilisées sont fournies dans les dossiers [home](https://github.com/Naedri/CDIN-BeBiker/tree/master/home), [about](https://github.com/Naedri/CDIN-BeBiker/tree/master/about) et [services](https://github.com/Naedri/CDIN-BeBiker/tree/master/services).

## Détails

### Zone utile (wrapper)

La zone utile est de `90%` de la largeur de la page, avec une largeur maximale de `1100px`.

### Typographie

#### Général

La police d'écriture utilisée pour le corps de texte est [Muli](https://fonts.google.com/specimen/Muli) (variante Regular et Bold). La taille du texte est `16px` avec une hauteur de ligne de `1.5`.

#### Titres

3 variantes de titres sont utilisées. Dans les 3 cas, la graisse de la police est `bold` et la hauteur de ligne est `1.15`. Seule la taille du texte change :

* Titre normal : `56px`
* Titre large : `64px`
* Titre small : `40px`


#### Menu

La police d'écriture utilisée pour le menu est [Pathway Gothic One](https://fonts.google.com/specimen/Pathway+Gothic+One) avec une taille de texte de `16px` et une graisse `bold`.

### Couleurs

Les couleurs utilisées sont les suivantes :

* Bleu principal (boutons, liens) : `#39d6c0` (`#03a48f` au hover)
* Noir (texte, menu, footer, sections sur fond noir) : `#000`
* Gris clair (fond de certaines sections) : `#f7f7f7`
* Gris foncé (élément du menu sélectionné et séparations entre les éléments du menu) : `#232425`

### Grille

La grille utilise les tailles de cellules suivantes :

* 1/2
* 1/3
* 2/3
* 1/4

De plus, il existe 3 tailles de gouttières :

* Aucune gouttière
* Gouttière normale (`16px`)
* Gouttière large (`48px`)

### Breakpoints

* L'affichage « mobile » se déclenche lorsque la fenêtre du navigateur est inférieure à `679px`.
* L'affichage « tablette » se déclenche lorsque la fenêtre du navigateur est inférieure à `769px`.
* L'affichage « desktop » se déclenche lorsque la fenêtre du navigateur est supérieure à `769px`.

## Techniques utilisées

* Méthode BEM pour le nommage des classes CSS
* Approche composants
* Grille de mise en page
* Responsive web design
