
# Interface / aide

## Modification de l'interface

- [x] More Minimap Autohide (0.17) : https://mods.factorio.com/mod/more-minimap-autohide-017 @license:MIT
	- permet de masquer la minimap, la barre du bas et les notifications! (Ctrl+M, Ctrl+B, Ctrl+N, etc)
	- license: MIT
	- TESTED, WANTED

# Deplacement

## Ameliore le déplacement a pied

* [x] Squeak Through : https://mods.factorio.com/mod/Squeak%20Through
	- Traverse un champ de panneaux solaires devient possible (on marche sur le bord), tout simple.
	- license: GNU GPLv3
	- TESTED WANTED

## Ameliore la conduite

- [x] https://mods.factorio.com/mod/Vehicle_Cruise_Control
	- avancer/reculer en toggle (ctrl+W/ctrl+S)
	- license: The Unlicense (Public Domain)
	- TESTED WANTED
	- TEST require: ctrl+W est bien pour un QWERTY mais en AZERTY ca donne quoi ? estce que ctrl+Z n'est pas dejà utilisé pour annuler (blueprint/construction) ?
	- TODO: indiquer a l'auteur d'afficher une info bulle avec le racourcis
	- Le cruise control empèche PavementDriveAssist de s'arreter
	- TODO: voir si on peut desenclancher l'auto-cruise lors de l'appuis de W/S

- [x] https://mods.factorio.com/mod/VehicleSnap
	- par angle de 1/16 (c'est réglable, je crois que je préfère 1/8)
	- license: MIT
	- TESTED WANTED

- [ ] https://mods.factorio.com/mod/PavementDriveAssist
	- autopilot sur route! trop fort! ca va nous faire construire des routes... encore mieux avec  https://mods.factorio.com/mods/Arcitos/AsphaltRoads
	- license: MIT
	- TESTED WANTED ENDGAME
	- TESTED: Fonctionne avec Vehicle_Cruise_Control sauf que le Cruise control empèche l'arret automatique
	- TESTED: PavementDriveAssist fonctionne bien avec VehicleSnap
	- TESTED: PavementDriveAssist a été testé, en décochant le besoin de recherche pour avoir la fonctionnalité


- [ ] https://mods.factorio.com/mods/Arcitos/AsphaltRoads
	-
	- TESTED WANTED ENDGAME
	- SeeAlso: https://mods.factorio.com/mods/Tone/More_Floors

## Ameliore l'usage des vehicules (et tourelles)

- [x] https://mods.factorio.com/mod/justgo
	- Lorsqu'on place un vehicule = On entre automatiquement dedans!
	- license: MIT
	- TESTED : ne fait rien = ne marche ?!

- [?] Fill4me : https://mods.factorio.com/mod/Fill4Me
	- charge du fuel dans un vehicule automatiquement (je veux!), ne s'applique pas aux tourelles placés par les drones.
	- charge des munitions automatiquement dans une tourelle (est-ce qu'on veut ?)
	- license: BSD-3-Clause
	- TESTED WANTED (pour l'auto fuel, mais l'auto munition est sympa aussi!)

- [?] Ammo Loader+ : https://mods.factorio.com/mod/ammo-loader
	- charge des fuel/munition auto => un peu trop automatisé ?
	- license: GNU GPLv3
	- not-tested

## Ajout de vehicules

- [ ] Hovercrafts : https://mods.factorio.com/mod/Hovercrafts
	- allons sur l'eau! trop bien!!! en + il est très sympa sur la terre aussi!
	- license: CC BY-SA 4.0
	- TESTED WANTED
	- TESTED bug avec electric-vehicle-lib-reborn (et LaserTank)

- [ ] Cargo Ships : https://mods.factorio.com/mod/cargo-ships
	- après les trains, des bateaux!
	- license:
	- not-tested


## Teleportateur

- [x] https://github.com/Klonan/Teleporters
	- Construire des téléporteurs pour les joueurs pour se déplacer de base en base
        - Teleporteur de base en base
	- license:
        - bon compromis face a "Portals"
        - partial-TESTED (necessite la recherche)

- [~] https://mods.factorio.com/mod/Portals
	- Un portalgun et une paire de portail orange et bleu pour chaque joueur! Mais où est GLaDOS ?!
	- license: GNU GPLv3
	- TESTED WANTED avec limite
	- TESTED : portal-gun, limon grenade

        - Des portalgun (et des grenades citron!)
        - Bug: permet de tricher en posant un portail bleu n'importe où (meme dans les zone non explorée)
        - Bien en "CreativeMod-like"
        - TODO: On peut limiter le bug en n'autorisant les portails qu'a "courte distance" : voir si cest une limite a la construction (proche du joueur) ou si ca limite la distance entre les 2 portails
        - WANTED
	TODO: voir si le mod a besoin de modif
	TODO: n'autoriser que les portails sur une surface *beton* ?


# terre/eau/pont

* [x] Beautiful Bridge Railway : https://mods.factorio.com/mod/beautiful_bridge_railway
	- Des ponts!
	- license: MIT
	- TESTED WANTED

* [ ] Expensive Landfill Recipe : https://mods.factorio.com/mod/ExpensiveLandfillRecipe
	- Augmentant le prix du ramblai (utilisons des ponts à la place!)
	- license: MIT


# INTERFACE / AIDE

* [?] https://mods.factorio.com/mod/RadarGridGuide
	- Aide a placer les radar régulièrement pour avoir une meilleur couverture
	- license:

- [x] https://mods.factorio.com/mod/ShowUnconnected
	- indication des éléments non connectés (ca montre des loupés et des bugs, dans notre partie existante ;-))
	- license: MIT
	- TESTED WANTED
	- need: pouvoir le desactiver (le rendu), utile mais chiant de voir clignoter des warnings partout.

- [x] https://mods.factorio.com/mod/speaker-signals
	- Plus d'icons !
	- license:

- [x] https://mods.factorio.com/mod/speaker-signals-expansion
	- Encore plus d'icons !
	- license:




# Aide a la construction

- [ ] https://mods.factorio.com/mod/GhostInHand
	- Utile lorsqu'on veut construire uniquement avec des ghost et laisser les drones faire le boulot
	- Inutile: car deja intégré dans les options du jeu 0.17 (a verifier si on a activé l'option)
	- Utile: pour avoir un bouton/racourcis rapide ?
	- license: MIT

* [ ] https://mods.factorio.com/mod/power-grid-comb
	- Permet de recabler les fils des réseaux électrique pour un resultat plus carré. Perfectionniste.
	- license:

- [ ] https://mods.factorio.com/mod/Logistic-Request-Manager
	- ?
	- license:

# DU BIO

- [?] Bio Industries : https://mods.factorio.com/mod/Bio_Industries
	- Ajoute des graines, etc. et de quoi recuperer des materiaux sur certains equipements crafté (four, etc) un peu comme "Reverse Factory"
	- license: MIT
	- partial-TESTED: ca a l'air bien (mais ca ouvre bcp de nouvelle possibilité)

- [?] Robot Tree Farm : https://mods.factorio.com/mod/robot_tree_farm
	- Les robots peuvent planter des arbres!
	- license: CC BY-SA 4.0
	- not-tested-yet

- [?] https://mods.factorio.com/mod/Bioluminescence
	- Ajoute des arbres bioluminescent (ce sont des arbres en + des arbres normaux)
	- Fonctionne pour une nouvelle partie. (qu'a la création du terrain?)
	- Ne fonctionne pas pour une partie existante ?
	- license: non-free! (Visible Source, No Public Derivatives)

## Outil pour regenerer le terrain

- [ ] Regenerate Terrain : https://mods.factorio.com/mod/regenerate-terrain
	- Testé sur la grande partie (ca prend un peu de temps, ca fait respawn les bitters et perdre la vision/exploration) mais ca marche.
	- license: non-free!


# recyclage

- [ ] Reverse Factory : https://mods.factorio.com/mod/reverse-factory
	- permet de recycle des objects et recuperer la matiere premiere
	- license: MIT
- [ ]

# More FUTURIST


- [x] https://mods.factorio.com/mod/aai-vehicles-laser-tank
	- Vraiment classe ! (meme si license nonfree)
	- license:

- [/] https://mods.factorio.com/mod/laser_tanks
	- Change l'apparence du tir lazer du tank
	- license: CC BY-SA 4.0
	- TESTED, BUG ! DONT-WANT
	- Le bug vient de la lib "Electric Vehicles Lib: Reborn" mod (le mod laser_tanks inclus la version 0.1.0) (le bug se reproduit sans laser_tank avec uniquement la lib, meme en version 0.1.2)
		- voir: Lehttps://mods.factorio.com/mod/Hovercrafts/discussion/5cc9c7712ff750000d6dbc2f

* [ ] https://mods.factorio.com/mod/laser_rifle si on a deja un lazer portatif pourquoi pas une arme ? trop cheaté ?

* [ ] arme trop dangeureuse ? https://mods.factorio.com/mod/railgun_enhancer ; https://mods.factorio.com/mod/railgun_revival



# ARMEMENT

- [ ] https://mods.factorio.com/mod/Turret-Shields
	- game def
	- license:
- [ ] https://mods.factorio.com/mod/uniturret



## cosmetic

* [ ] https://mods.factorio.com/mod/MushroomCloud

* [ ] https://mods.factorio.com/mod/Concretexturex




# organisation

- [x] helmod :
	-
	-
	- TODO: helmod -> demander un sample de donnees ?

- [ ] Actual Craft Times Remade : https://mods.factorio.com/mod/actual-craft-times-remade
	- TESTED: bug?! ca n'affiche rien la ou ca devrait...
	-

 - [ ] https://mods.factorio.com/mod/what-is-it-really-used-for
	-
	-

# Reseau electrique

- [ ] https://mods.factorio.com/mod/Transformers
	- Permet de charger des accumulateurs locaux, energie de secours?
	- license: MIT






# STOCKAGE

* [ ] https://mods.factorio.com/mod/better-storage-tanks
	- des gros coffres (on veut vraiment ?!)




- [ ] https://mods.factorio.com/mod/bullet-trails
	- Cosmetic, balle tracante
	- license: non-free!


# ?

- [ ] https://mods.factorio.com/mod/EvenMoreLights

- [ ] (0.16 only) https://mods.factorio.com/mod/attach-notes
	- Des pancartes!
	-

# Sound/Music

https://mods.factorio.com/mod/original-music-hd-updated










# Pour moder :
https://mods.factorio.com/mod/DataRawSerpent


la terre est brulée
https://mods.factorio.com/mod/ScorchedEarth





Tester le jeu avec tous les mods de OwnlyMe ?
- couleur des resources, Reasonable Color ...
- les arbres/sol : https://mods.factorio.com/mod/unlushed_trees
 -apparence realiste : https://mods.factorio.com/mod/better_ore_icons


# FUN LOL

- [ ] Ball Biters : https://mods.factorio.com/mod/BallBiters
	- Au revoir les cafards, bonjour les balles! #FUN #LOL
	- license: MIT
	- TESTED FUN


# DELIRANT


Change la couleur (un peu) des belt/usine/ https://mods.factorio.com/mod/reasonable-colours


Lumiere : https://mods.factorio.com/mod/lightorio




# a voir ...



- https://mods.factorio.com/mod/ZRecycling

- https://mods.factorio.com/mod/belt-brush

- https://mods.factorio.com/mod/artillery-bombardment-remote


# FUN  CRAZY

crazy!! grafana : https://mods.factorio.com/mod/graftorio



# Mort

* [ ] https://mods.factorio.com/mod/DeathNotice (Possible BUG!)
* [ ] Cadavre de joueur n'est plus limité dans le temps : https://mods.factorio.com/mod/infinitycorpeslive (non-free)

( https://mods.factorio.com/mod/auto-research )

# pas compris :https://mods.factorio.com/mod/pipelayer

- Lua prog : https://mods.factorio.com/mods/tesseractcat/scriptable-drones




https://mods.factorio.com/mod/secondary-chat


https://mods.factorio.com/mod/QoL-TempStations

https://mods.factorio.com/mod/Shortcuts
	-> voir les boutons pour deplacer, il faudrait la meme chose dans helmod

https://mods.factorio.com/mod/TrainSkipFulfilledStation
https://mods.factorio.com/mod/Automatic_Train_Painter

https://mods.factorio.com/mod/aai-zones

Modding : https://mods.factorio.com/mod/YouModRecipe

https://mods.factorio.com/mod/building-platform
