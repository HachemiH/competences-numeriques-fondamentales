# 1 Les composants informatiques - C1

# Table des matières

  * [Le processeur](#le-processeur)
  * [La mémoire vive](#la-memoire-vive)
  * [La carte mère](#la-carte-mere)
  * [La carte graphique](#la-carte-graphique)
  * [Le clavier](#le-clavier)
  * [La souris](#la-souris)
  * [L'écran](#ecran)


## <a name="le-processeur">Le processeur</a>

Le processeur appelé aussi avec son terme anglais `CPU` (Central Processing Unit) que l'on pourrait traduire par "unité centrale de traitement".

Son rôle est central dans le fonctionnement d'un ordinateur, il s'occupe de tous les calculs qui sont nécessaires au bon déroulement d'une tâche,  que ce soit l'affichage d'une image, un calcul de taux de TVA, la lecture d'une vidéo, etc …

![Processeur Intel CoreI7](img/processeur-intel-core-i7-7700-3-6ghz.jpg)

Il n'a qu'une seule et unique fonction, il ne fait que des opérations mathématiques. D'ailleurs on peut évaluer la puissance d'un processeur au nombre d'opérations qu'il peut effectuer à la seconde. L'unité de mesure est le GHz (Giga Hertz).

[Giga](https://fr.wikipedia.org/wiki/Giga) pour Milliard et [Hertz](https://fr.wikipedia.org/wiki/Hertz) pour le nombre de répétitions à la seconde.

Dans l'informatiques grand publique on évalue donc la puissance d'un processeur au nombre de milliards d'opérations qu'il peut effectuer à la seconde.

Par exemple le processeur ci-dessus en photo est le "Intel CoreI7" cadencé à 3,6 GHz (3 milliards 600 millions d'opérations à la seconde).

Il existe plusieurs type de processeurs, en fonction des usages. Dans l'informatique grand publique, on peut distinguer 2 grands types de processeurs : 

* `X86` / `AMD64` : le processeur des ordinateurs de bureau et laptop (ordinateurs portables)
* `ARM` : le processeur des appareils mobiles (téléphones mobiles, tablettes, etc…)

Ce qui va notamment différencier ces deux processeurs, sont la consommation électrique, évidemment l'ARM a été spécialement conçu pour être extrêmement économe en termes d'énergie au détriment d'une puissance un peu moindre.

Les processeurs modernes disposent de plusieurs cœurs, les plus courants disposent de 4 ou 8 cœurs. 
Multiplier le nombre de cœurs a été la façon la plus simple de continuer à augmenter la puissance des processeurs puisque on avait atteint une limite physique de miniaturisation des processeurs.



## <a name="la-memoire-vive">La mémoire vive</a>


On pourrait considérer la mémoire vive (appelée aussi mémoire `RAM` pour "Random Access Memory") comme "une mémoire tampon". Plus son espace est grand et plus on peut lancer de tâches en parrallèle.

![Mémoire Vive](img/memoire-vive.jpeg)

On évalue sa capacité de stockage en octets (Bytes en anglais), les tailles moyennes de mémoire vive disponible sur les ordinateurs grand publique de nos jours entre 4 Go (4 Giga Octets ou 4 Giga Bytes en anglais) pour les machines d'entrée de gamme et 32 Go pour les machines haut de gamme, mais évidemment cela est en constante évolution.

La taille ne suffit pas pour évaluer la qualité d'une mémoire vive. En effet il y a une seconde caractéristique qu'il faut prendre en compte lorsqu'on est préoccupé par la performance, c'est la cadence d'exécution qui s'exprime en Mega Hertz.

Et le dernier critère à prendre en compte est la génération de mémoire vive, actuellement la génération la plus récente dans le commerce est la DDR4 (plus le chiffre est grand, plus la génération est récente ). La DDR5 est en approche mais pas encore commercialisée.

Son rôle est garder "vivantes" les tâches en cours, c'est elle qui donne les jeux d'instructions à traiter au processeur et qui reçoit également son résultat.

Cette mémoire est dite vivante, parce que son contenu est stocké uniquement pendant que la machine est allumée. Elle est remise à zéro dès qu'on éteint cette dernière.

L'exemple le plus courant est le texte qu'on travaille sur un éditeur de texte type Libre Office Writer ou Microsoft Word, et qu'on a pas sauvegardé, tant que l'ordinateur est allumé le texte est accessible et visible et stocké en mémoire vive, mais si une mise hors tension survient sans prévenir et que l'on a pas sauvegardé son travail, tout est perdu.




## <a name="la-carte-mere">La carte mère</a>

La carte mère comme son nom peut l'indiquer, est l'élément qui met en relation tous les composants de l'ordinateur.
Elle sous la forme d'une grande plaque éléctronique pourvue de différents emplacements appelés "slots" pour chaque type de composants (processeur, mémoire vive, carte graphique, etc…).


![Carte Mère](img/carte-mere.jpeg)

Les cartes mères modernes sont fournies avec des composants(basiques) directement intégrés : 
* carte son
* carte graphique
* carte réseaux (filaire + wifi)
* ports `USB`
* ports vidéo 



## <a name="la-carte-graphique">La carte graphique</a>

La carte graphique est le composant qui a pour unique tâche de s'occuper de l'affichage graphique.
Elle est construite autour d'un `GPU`(Graphics Processing Unit), c'est une sorte de processeur spécialement dédié au calculs lié à l'imagerie.


![Carte Graphique](img/carte-graphique.jpg)

Elle possède également son propre espace mémoire dédiée à ses tâches. Cette mémoire peut être en `DDR` ou en `GDDR` (qui est un type de mémoire spécialement conçu pour les `GPU`).

C'est un composant extrêmement puissant en terme de puissance de calcul.
Sa puissance de calculs brute est telle, qu'elle souvent utilisée par les mineurs de cryptomonnaies.

Les deux types de cartes graphiques les plus répandus dans le commerce sont les Geforce de Nvidia et les Radeons de AMD.


## <a name="le-clavier">Le clavier</a>

Le clavier est ce qu'on appelle un périphérique d'entrée. C'est à dire que c'est un périphérique sur lequel on va entrée des données vers l'ordinateur.

Il faut distinguer 2 parties principales sur un clavier : la partie physique et la partie logicielle.

![Clavier](img/clavier-mecanique.jpg)

Dans la partie physique, les claviers se démarquent par leurs construction :

* Le clavier à membrane (le plus répandu, notamment sur les ordinateurs portables et le plus silencieux)
* Le clavier mécanique (le plus répandu chez les gamers, le plus robuste et le plus précis, mais également le plus bruyant)
* Le clavier visuel ou virtuel (disponible dans tous les systèmes d'exploitation)


Dans la partie logicielle appelée aussi `layout` on a une quantité énorme de types différents :

* `Azerty`
* `Qwerty`
* `Qwertz`
* `Dvorak`
* etc…

Selon le pays dans lequel vous résidez, la disposition des claviers peut être très différente selon la langue.
En France par exemple, le clavier le plus répandu est l'`Azerty`. Il existe des alternatives plus ergonomiques comme le `Bépo`.




## <a name="la-souris">La souris</a>

La souris est considérée comme un périphérique d'entrée. Elle est utilisée pour manipuler les documents, objets, la navigation, etc…

Il existe une grande quantité de modèles différents, mais on peut constater deux grands types : les souris filaires et les sans fil.

![Souris](img/souris.jpg)

Les souris sont conçues avec au moins deux clics (gauche et droite) et une roulette pour le défilement, mais sur des modèles de milieu et haut de gamme on peut avoir beaucoup plus de boutons et options de confort.

Il existe des alternatives à la souris classique :

* Trackpad (dispositif de pointage sur les ordinateur portables)
* Trackball (la souris ne bouge pas, le curseur bouge avec une boule)
* La souris verticale (une souris ergonomique)
* Magic Trackpad (trackpad sans fil Apple)



## <a name="ecran">L'écran</a>

L'écran est un périphérique de sortie, puisque son rôle est d'afficher les informations de l'ordinateur.

Il existe une multitude de type d'écran pour une multitude d'usages différents, cela peut aller du gaming, jusqu'à la retouche photo, etc…

![Écran](img/ecran.png)

La première caractéristique de choix de l'écran est sa taille qui est exprimée en `pouces` (d'un coin de la diagonale, jusqu'au coin opposé). Cela peut aller de 13 pouces pour les petits ordinateurs portables, jusqu'à des 32 `pouces` pour le bureau les plus courants.

De nouvelles tailles d'écrans commencent à faire leurs apparitions pour des "écrans nouvelle génération" qui sont dans des formats de plus en plus large.

Une autre caractéristique pour qualifier la qualité d'un écran, est la résolution. Celle-ci défini le nombre de pixels (points) que l'écran est capable d'afficher. 

Une dernière caractéristique principale à prendre en compte est le `PPP` (Pixel Par Pouce), elle représente la densité des pixels de l'écran. Plus ce chiffre est élevé, plus belle est la qualité de l'image.


