## tutoriels
### Comment utiliser VoyantTools pour explorer le corpus textuel des rapports académiques transcrits.

#### À propos de Voyant Tools
Voyant Tools est un environnement d’analyse, de lecture et de visualisation de textes numériques.

Voici deux ressources indispensables avant de s'y plonger :
* [le tutoriel d'Aurélien Berra](https://github.com/aurelberra/voyant_tools/blob/master/tutorial/voyant_tools_intro_fr.md) qui revient également sur la genèse et les objectifs de Voyant Tools.
* [la documentation officielle de l'outil](http://voyant.tools.huma-num.fr/docs/#!/guide/start)

#### Rappel du corpus

Sur les 603 rapports issus de la base de données, nous avons sélectionné les 521 rapports ayant une transcription.
Deux modes d'accès :

#### 1ère étape : importer les données

* Le jeu de données initial est [à télécharger ici](./datasets/datasets.md) sous format CSV
* Accéder directement au corpus pré-paramétré dans [le projet voyant-tool](http://voyant.tools.huma-num.fr/?corpus=9f0929de55123b653c9475a6be733db4)

#### 2ème étape : Accès à l'interface

L'interface s'ouvre avec 5 modules par défaut dont un le lecteur qui affiche l'ensemble de votre corpus. L'ensemble des rapports est donc lisibles par ordre chronologique de rédaction.

![](../images/voyanttools_02.png)

Chaque module possède dans son angle en haut à droite, un lot d'icône qui s'affiche au survol. A ce niveau, vous pouvez soit ajuster le module actuel par différentes options, soit réaliser un export de la visualisation soit choisir un autre module selon vos besoins.

![](../images/voyanttools_etape1.gif)

Dans les actions et les options de bases qui se retrouvent dans la plupart des modules, il faut en noter trois principales :

* la recherche de mots
![](../images/voyanttools_4.png)

* la sélection de l'ensemble du corpus ou uniquement certains rapports
![](../images/VoyantTools_7.png)

* l'exclusion de mots-vide, paramétrage des **stopwords**


#### Quelques exemples d'utilisation

##### Le module "Correlation"

Il vous permet d'afficher après un choix de termes de votre choix, sous forme de liste, toutes les réponses mais dans leurs contextes du document, c'est-à-dire en vous affichant directement les quelques mots avant et après. 
Par exemple, en cherchant "blâm*", vous verrez d'une part, toutes les variantes (blâme, blâmera, blâmant, blâmable, etc.), mais également sous une forme abrgée, le contexte du mot et dans quel document il s'agit. De plus, si vous cliquez sur une des lignes, le module "Lecteur" juste au-dessus se met à jour et vous permet d'accéder à l'ensemble du rapport.

 ![](../images//voyanttools_5.png)

##### Le module "Terme du document"

Proche du module précédent d'autant qu'il peut être connecté au module "Corrélation", ce module permet, après avoir choisit différents termes d'avoir n'information du nombre d'occurence par document

 ![](../images/VoyantTools_6.png)
