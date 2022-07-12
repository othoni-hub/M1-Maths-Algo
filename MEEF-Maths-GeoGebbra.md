# **MEEF Maths - GeoGebra**


<img src="https://sciences-lestonnac.fr/wp-content/uploads/2014/11/geogebra.jpg" width="230" height="220" align ="right"/>

<p>
    
</p>

**O.Thöni - UCO**
*document à l'usage exclusif des personnes concernées par la formation Master MEEF - Maths de l'UCO*

###### tags:  `MEEF-Maths`, `Geogebra`

## ***Objectifs :***

2 heures pour :
* *Consolider éventuellement le maniement du logiciel Geogebra dans ses multiples dimensions*
* *Mener une réflexion didactique sur l'usage de Geogebra*

---

**Table des matières**
[TOC]


---

## **La bible de GeoGebra**

--> téléchargeable ici, avec tous les fichiers d'accompagnement : https://tice.univ-irem.fr/lexique/co/Annexe_F_-_Telecharger_le_document_complet.html 

<iframe width="100%" height="500" src="https://tice.univ-irem.fr/lexique/co/site.html" frameborder="0"></iframe>

https://drive.google.com/file/d/1IB2r0n3d2mWIJo5KZ7pP_ourDOfObIfN/view?usp=sharing


## **1<sup>ère</sup> activité : "approche de la notion de fonction"**

### **1°) faire une proposition**

### **2°) Analyse de la plus value-didactique (*SAMR*)**

![](https://i.imgur.com/vHmgXaN.png =400x280)


### **3°) Proposition OT**

####  Le scenario
  
Dans une classe de 3<sup>ème</sup> , en salle informatique, équipée d'un ensemble de vidéoprojection, les élèves ont à effectuer l'activité suivante, réinvestissant le théorème de Thalès et amenant à découvrir la notion de fonction : 
en résumé, à un carré de côté « $x$ », on associe, dans un 1<sup>er</sup> temps un segment dont la mesure de la longueur en cm est égale à la mesure de l'aire du carré en cm² ; 
après avoir prouvé la relation géométriquement, on effectue la figure dans un logiciel de géométrie dynamique,
puis on fait un relevé de valeurs dans un tableau récapitulatif, on pourra réaliser ultérieurement un graphique sur papier avec ces données.
Le logiciel de géométrie dynamique permet de visualiser l'évolution conjointe de ces deux longueurs, grâce à l'outil de tracé de lieux géométriques.
Puis, dans un 2<sup>nd</sup> temps, on passe dans le tableur (le logiciel GeoGebra est idéal pour basculer ainsi d'un point de vue à un autre !).
On finira enfin par l'aspect fonctionnel, en traçant, toujours dans le même interface, la fonction liant les deux longueurs étudiées.

#### L'énoncé de l'activité et la mise en œuvre dans GeoGebra
 1. Aspect Géométrique
 
 a) Tracer la figure
 
 * ABDC est un carré. Par commodité, A est placé à l'origine du repère de GeoGebra, et B sur l'axe des abscisses, il est "libre", c'est-à-dire qu'on pourra l'y faire coulisser avec la souris (on évitera cependant de l'emmener à gauche de A). 
* Puis, on trace le cercle de centre A et de rayon 1 cm.
      Il coupe la droite (AB) en F. La parallèle à (CF) passant par B coupe (AC) en E.
     
![](https://i.imgur.com/5hqTtMk.png =530x400)

 b) Démontrer
 
* On nomme « $x$ » la longueur variable AB. Démontrer que AE = $x²$.

 2. Visualiser l'expression "en fonction de..."
 
 a) Laisser des traces
 
* Placer le point M de telle sorte que ABME soit un rectangle. Quelles sont les coordonnées de M dans le repère de GeoGebra ?
      Faites un clic droit sur M et cliquez sur « Trace activée » :     
      
![](https://i.imgur.com/XUHSNwM.png =400x280)

* Observez le déplacement du point M lorsque l'on déplace le point B.

 3. Débranchons un peu...
 
 a) Relevé de valeurs et graphique (à la main)

* Dressez un tableau dans lequel vous relevez manuellement différentes valeurs de la longueur AB = $x$ du côté du carré, et la longueur MB = AE = $y$, 
* puis, sur une feuille de papier millimétré, réalisez un graphique donnant « $y$ en fonction de $x$ ».

(C'est toujours mieux quand on sait faire à la main ce que l'on demande à l'ordinateur...)

 4. Automatisons le calcul de valeurs et le graphique
 
 a) Le tableur
* Dans le menu « Affichage », cochez « Tableur ».
![](https://i.imgur.com/eZyXmiT.png =300x200)

* En colonne A, créez une liste régulière de différentes valeurs de $x$,
* puis en cellule B2, insérez la formule qui permet de calculer la longueur de BM = AE = $y$
* et tirez-la vers le bas
![](https://i.imgur.com/Bj5gpPW.png)

* Sélectionnez vos deux colonnes, faites un clic droit et demandez « Créer une liste de points ».
Qu'observez-vous ?

![](https://i.imgur.com/HH8ccQ0.png)

* Dans l'avant dernier menu, sélectionnez « Boite de sélection des objets à Afficher/Cacher », 
![](https://i.imgur.com/euKJe8h.png =420x400)

* Créez une case à cocher qui permettra d'afficher ou de masquer ces points de la liste que vous venez de fabriquer (il faut les sélectionner un à un...).
![](https://i.imgur.com/2lzED3W.png =300x200)

 5. Le passage délicat...
 
 a) de "en fonction de..." à la notion mathématique de "fonction"

* On a dit que la longueur $y$ était « fonction de » la longueur $x$. 
      Une fonction est une « boîte à calculs », définie par une formule de calcul, ici, si on appelle « $f$ » cette « boîte à calculs », quand on entre une valeur de $x$, la « boîte à calculs » ressort la valeur de $y$.
      
      
* Quelle est la formule contenue dans cette boîte à calcul ? Cette formule s'appelle " l'expression de la fonction "
* Dans la « barre de saisie » située en bas de l'écran de GeoGebra, écris l'expression de la fonction f : « $f(x) = x^2$ » 
      (Remarque l'accent circonflexe pour calculer une puissance)
      Valide par "Entrée"
* l'**expression** " $f(x) = x²$ " doit être comprise ainsi :" la fonction $f$, de $x$, fait $x²$ ". 
      Par habitude, on lit " $f$, de $x$, égale $x²$"
      Il est important de bien donner du sens à chaque mot !

![](https://i.imgur.com/ukYyQnk.png)

* GeoGebra trace alors dans son repère la représentation graphique de la fonction f, c'est-à-dire l'ensemble des points de coordonnées $(x ; f(x))$.
* Fabrique une case à cocher pour Afficher/Masquer cette courbe.
      Qu'observes-tu ?

![](https://i.imgur.com/xWRaBhU.png)

* Pour résumer cette "fonction-boîte à calculs", on emploie la notation suivante : 

$$f : x \mapsto f(x)$$

ce que l'on lit "la fonction, qui, à $x$, associe $f(x)$"... Ah, cette manie d'inverser les compléments d'objets indirects... (*"Contre nous de la tyrannie-euh l'étendard sanglant-t-est levé"*)

Elle signifie " la fonction $f$, qui, du nombre $x$, fait $x²$ "

#### Conclusion !
Dans cette activité, nous avons vu comment... :
    • utiliser la barre de saisie. 
      Notez que pour définir un point par ses coordonnées dans la barre de saisie, on utilisera la syntaxe : F = (0,1), même si cela requiert quelque concession vis-à-vis de nos habitudes de rigueur dans les notations... 
    • faire afficher la trace d'un point mobile lors du déplacement d'un autre point lié à un objet.
    • saisir l'expression d'une fonction pour obtenir sa représentation graphique.
    • créer une boîte de sélection pour afficher/cacher un élément.
    • utiliser le tableur (référence relative aux cellules, formule, recopie,...).
      Notez que les éléments du tableur sont réutilisables en fenêtre géométrique, et réciproquement.
    • fabriquer une liste d'éléments (nombres ou points)
    
>**Attention :**
>Un inconvénient possible, plus tard, de GeoGebra, réside dans cette confusion entre la fonction, son expression et sa représentation graphique.
>C'est une question récurrente, voire décapante, des oraux de CAPES...
Heureusement, la fonctionnalité de calcul formel va permettre de pallier cette difficulté.

https://www.geogebra.org/m/dq542qmt

<iframe width="100%" height="500" src="https://www.geogebra.org/m/dq542qmt" frameborder="0"></iframe>



---

## **2<sup>ème</sup> activité : "Mise en place du calcul formel"**

### **1°) faire une proposition**

### **2°) Proposition OT**

Cette activité a été réellement vécue, dans une classe de 4<sup>ème</sup>, point important, qui fait tout le sel de l'activité, nous ne savons pas encore résoudre une équation...

#### **1<sup>ère</sup> partie : comprendre l'intérêt de mathématiser un problème par une équation**

* **Question 1 :**
      Un client commande par internet 8 produits identiques.
      Le colis lui coûte 12,80 €, frais de port compris de 2,16 €
      Quel est le prix d'un article ?
* **Question 2 :**
      Sur la piste d'athlétisme, j'ai observé que pour courir 5 tours, si je retire une minute, j'obtiens exactement le même temps qu'en faisant 2 tours et en rajoutant 3 minutes.
      Quel est mon temps au tour ?
      
      
**Recherche :**

* Certains binômes d'élèves arrivent assez vite à la réponse à la 1<sup>ère</sup> question, d'autres, spontanément, ouvrent le tableur de GeoGebra. Parmi ceux-ci, certains tâtonnent, par un procédé proche de la dichotomie (« c'est plus / c'est moins »), d'autres, plus systématiques, écrivent une liste de nombres, et calculent en face, par une formule tirée vers le bas, le prix correspondant.
* Pour le second problème, la situation est plus compliquée, d'abord car le nombre inconnu intervient dans deux expressions qu'il faut rendre égales, ensuite, et surtout, parce que le nombre à trouver n'est pas un nombre décimal (d'ailleurs, il ne se posent pas la question des nombres décimaux de minutes)... 
      Hé ! Hé !
* Les élèves introduisent, mais pas tout de suite, un mot, puis une lettre pour prendre la place de la quantité inconnue dans leur calcul, le bouche-à-oreille aidant un peu... Ils parviennent donc tous à poser les deux équations. Les premières règles font vaguement surface, grâce à la question 1.

#### **2<sup>ème</sup> partie : s'afranchir des techniques de résolution de ces équations**
* C'est là que je reprends (discrètement) la main pour proposer de découvrir un outil qui nous permettra de résoudre nos équations : le module de calcul formel de GeoGebra, disponible via le menu «Affichage».

![](https://i.imgur.com/peAP9oD.png =500x230)

L'écriture fractionnaire leur semblant superfétatoire, les élèves préfèrent la résolution approchée, ce qui m'arrange pour la suite...

![](https://i.imgur.com/HiJFUCy.png =500x60)

Ceci enclenche, bien sûr une discussion car ils ont bien vu dans le tableur que cette réponse n'était pas bonne... La résolution exacte redonne du crédit à l'écriture fractionnaire, qui amène à se poser la question de ce que représentent 4 tiers de minute... 
J'aime bien quand je ne sers pas à grand-chose...

S'ensuivent alors divers autres problèmes conduisant à des équations, y compris du 2<sup>nd</sup> degré, et d'autres qui n'ont pas de solution, ou pas de solution valable, car sortant du domaine des valeurs possibles, ceci faisant systématiquement ressentir le besoin de vérifier d'une part que la valeur est bien solution de l'équation écrite, et d'autre part, qu'elle répond bien au problème posé.
Nous formalisons ensemble une méthode un peu systématique pour résoudre ce genre de problèmes.
Et nous ne savons toujours pas résoudre une équation !

#### **3<sup>ème</sup> partie : poser les règles pour résoudre ce genre d'équations**

* *Expliquez ce qui s'est passé dans votre tête pour trouver la bonne valeur dans la question 1.
      - On a enlevé les frais de port, puis on a divisé par 8
      - Voici comment procéder dans le calcul formel de GeoGebra...*
      
![](https://i.imgur.com/lH1Vvx2.png =260x280)

* *Procédez de même avec l'équation de la question 2 : $5x - 1 = 2x + 3$*

Ne reste qu'à formaliser les règles de transposition dans les équations...
L'activité aura permis de se délester des calculs et de se concentrer sur les démarches.

https://www.geogebra.org/m/pve3q7yk
<iframe width="100%" height="500" src="https://www.geogebra.org/m/pve3q7yk" frameborder="0"></iframe>


https://www.geogebra.org/m/s89kph5a

<iframe width="100%" height="500" src="https://www.geogebra.org/m/s89kph5a" frameborder="0"></iframe>

### **3°) Analyse de la plus value-didactique (*SAMR*)**

### **4°) Exercice (à traiter plus tard)**

Il s'agit d'un problème très classique, mais on n'est jamais obligé de tout réinventer, surtout pas l'eau chaude, les problèmes de robinets appartiennent au passé... Plaçons-nous dans une classe de 1<sup>ère</sup>...
* Le problème :
      *Un industriel reçoit des plaques de PVC de dimensions 21 cm sur 29,7 cm. Il veut fabriquer des boîtes, par découpe laser et thermopliage, en suivant le patron ci-dessous :*
![](https://i.imgur.com/yfKN70f.png)

* *L'ingénieur l'informe que le volume de la boîte est maximal lorsque la longueur x vaut 4 cm.
      Qu'en pensez-vous ?*

**Remarque : n'oubliez pas : vous êtes en classe de 1<sup>ère</sup> !**

**Conseil :** On lira avec profit le très bon document sur le calcul formel avec GeoGebra émis en juin 2014 par l'Académie de Poitiers ! --> https://ww2.ac-poitiers.fr/math/sites/math/IMG/pdf/geogebra-calculformel.pdf



https://www.geogebra.org/m/g2ndfezp

<iframe width="100%" height="500" src="https://www.geogebra.org/m/g2ndfezp" frameborder="0"></iframe>


---

## **3<sup>ème</sup> activité : "Géométrie 3D :  cône inscrit dans une sphère"** 

### **1°) proposition OT**

Dans cet exercice, nous allons mettre en œuvre toutes les fonctionnalités de Geogebra : le début : modélisation 3D et vue plane, ainsi que l'écriture de la fonction décrivant le volume sont accessibles à des élèves de 3<sup>ème</sup>, la recherche du maximum en réalisant la démarche dans le module de calcul formel, ce qui affranchit des calculs, concerne les élèves de 1<sup>ère</sup>.

**but :**
*Un cône est inscrit dans une sphère, on cherche la configuration qui rend le volume du cône maximal.*
* *Dans le module 3D de Geogebra, dessiner une sphère de centre 0, un cône inscrit dans la sphère, de centre O' et de sommet S, tous deux sur l'axe des abscisses, et de rayon O'B, B étant lui aussi dans le plan $xOy$.
      (Pour que le cône soit inscrit dans la sphère, il faut que le cercle de centre O' et de rayon O'B et que le sommet S soient sur la sphère.)
      On appelle *L* la mesure algébrique OO' (l'abscisse du point O').*
      
**Astuce :** en plaçant ainsi les points majeurs dans le plan $xOy$, on accède à la vue plane en fenêtre graphique 2D, ce qui permettra de mieux repérer les configurations planes où effectuer les calculs !
Remarque : on peut définir le rayon $R$ de la sphère et la "longueur" $L$ par des curseurs.


![](https://i.imgur.com/zlEdv5R.png)

Pour un $R$ donné, exprimer en fonction de $L$, le volume $V( L)$ du cône et représenter la fonction d'expression $V( L)$, dans une 2<sup>ème</sup> fenêtre graphique 2D.

(En 1<sup>ère</sup>)
* Dans la fenêtre de calcul formel, le rayon *r* de la sphère étant fixé, définir la fonction qui à un *l* réel associe *v( l )*, et rechercher ses extremums. Conclure.
      On pourra calculer le volume maximal du cône et le comparer à celui de la sphère.
      
**Remarque :**

Démontrer que la valeur $l_0 = -1/3 r$ , proposée par le module de calcul formel, réalise bien le maximum de $v$, est accessible en 2<sup>nde</sup>, il "suffit" de montrer que, toutes les valeurs autour donnent un volume inférieur, c'est-à-dire que, pour tout $h$ non nul de l'intervalle $[\frac{-2}{3} r ; \frac{4}{3} r]$, 
$v( l_0 + h)<v( l_0 )$...
ça se fait... avec une bonne classe...

![](https://i.imgur.com/nDgt9Ps.png)

**Fondamental :**

Nous avons été obligés de changer les noms de nos « variables », en prenant des majuscules dans la partie géométrique et algébrique, et minuscules dans la zone du calcul formel. Ceci nécessite une petite explication, qui réside dans l'ambiguïté du mot « variables ».
Du côté géométrique, $R$, $L$, $V$ étaient des variables au sens informatique du terme : des objets qui ont un nom, un type, et une valeur. L'objet $V$ n'est, on l'a vu, que l'expression de la fonction $V$. Dès lors que $R$ et $L$ ont une valeur, ils ne sont plus variables, par définition...
Du côté calcul formel, les variables $r$ et $l$ sont à entendre au sens mathématique du terme : ce sont des objets formels, qui prennent toutes les valeurs que l'on veut dans l'intervalle qui leur convient. La fonction $v$ est alors définie comme objet formel "fonction numérique", sa dérivée aussi.

https://www.geogebra.org/m/GfVrhws6

<iframe width="100%" height="500" src="https://www.geogebra.org/m/GfVrhws6" frameborder="0"></iframe>


### **2°) Exercice (à traiter plus tard)**

Vous l'aurez sans doute remarqué, la commande "patron" de GeoGebra ne concerne que les polyèdres...
Qu'à cela ne tienne !

*Réaliser le patron d'un cône connaissant son rayon et sa hauteur (Utiliser GeoGebra, les fenêtres 2D et 3D, et associer ces deux variables à des curseurs.)*

https://www.geogebra.org/m/p3ufnqan