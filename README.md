# fpga_starter_guide
Pour découvrir le fonctionnement d'un fpga et l'utiliser

## Avant de demarrer

### Qu'est-ce qu'un FPGA

Field-programmable gate array ou réseau de portes programmables. Sont souvent utiliser pour du prototypage de circuits intégrés Spécialisés(ASIC) : https://fr.wikipedia.org/wiki/Circuit_logique_programmable

### De quoi ai-je besoin?

* Un FPGA :)
* Un environnement de développement
* Quelques notions d'électronique et d'algebre de bool
* Quelques notions en dev logiciel
* Beaucoup de patience

#### Quel FPGA

Je recommande le ice40 de chez lattice car il y a eu un grand travail de retroingénieurie dessus, ce qui permet d'utiliser une chaine de developpement entierement libre. De plus il est assez puissant pour faire des projets interessant tel que le prototypage d'un microprocesseur ou même d'un microcontrolleur.

http://www.latticesemi.com/Products/FPGAandCPLD/iCE40.aspx

De nombreux model sont disponible et le plus simple à prendre en main pour un débutant semble être le "icestick ice40 hx1k". Il se branche en USB et peut être programmé depuis l'USB.

http://www.latticesemi.com/en/Products/DevelopmentBoardsAndKits/iCEstick

Il vaut une trentaine d'euro TTC en France.


#### Quel environnement de developpement (IDF)

http://www.clifford.at/icestorm/

#### En savoir plus

http://www.clifford.at/papers/2015/icestorm-flow/

## Tester le fpga

### Installation de la chaine d'outils



### faire clignoter les leds

## Projets sympa

### processeur j1a + interpreteur forth(swapforth)

http://www.excamera.com/sphinx/article-j1a-swapforth.html
