
# Interface / aide

## Modification de l'interface

- More Minimap Autohide (0.17) : https://mods.factorio.com/mod/more-minimap-autohide-017
	- [x] TESTED
	- [x] WANTED
	- permet de masquer la minimap, la barre du bas et les notifications! (Ctrl+M, Ctrl+B, Ctrl+N, etc)
	- license: MIT
	- J'ai fais une variante de ce mod pour mes propres besoins.
	- TODO: améliorer la variante et contribuer en upstream

# Déplacement

## Améliore le déplacement à pied

- Squeak Through : https://mods.factorio.com/mod/Squeak%20Through
	- [x] TESTED
	- [x] WANTED
	- Traverse un champ de panneaux solaires devient possible (on marche sur le bord), tout simple.
	- license: GNU GPLv3

## Améliore la conduite

- https://mods.factorio.com/mod/Vehicle_Cruise_Control
	- [x] TESTED
	- [x] WANTED
	- avancer/reculer en toggle (ctrl+W/ctrl+S)
	- license: The Unlicense (Public Domain)
	- TEST require: ctrl+W est bien pour un QWERTY mais en AZERTY ca donne quoi ? estce que ctrl+Z n'est pas dejà utilisé pour annuler (blueprint/construction) ?
	- TODO: indiquer a l'auteur d'afficher une info bulle avec le racourcis
	- Le cruise control empèche PavementDriveAssist de s'arreter
	- TODO: voir si on peut desenclancher l'auto-cruise lors de l'appuis de W/S

- https://mods.factorio.com/mod/VehicleSnap
	- par angle de 1/16 (c'est réglable, je crois que je préfère 1/8)
	- [x] TESTED
	- [x] WANTED
	- license: MIT

- https://mods.factorio.com/mod/PavementDriveAssist
	- autopilot sur route! trop fort! ca va nous faire construire des routes... encore mieux avec  https://mods.factorio.com/mods/Arcitos/AsphaltRoads
	- [x] TESTED
	- [x] WANTED
	- [x] ENDGAME
	- license: MIT
	- [x] TESTED: Fonctionne avec Vehicle_Cruise_Control sauf que le Cruise control empèche l'arret automatique
	- [x] TESTED: PavementDriveAssist fonctionne bien avec VehicleSnap
	- [x] TESTED: PavementDriveAssist a été testé, en décochant le besoin de recherche pour avoir la fonctionnalité


- [x] https://mods.factorio.com/mods/Arcitos/AsphaltRoads
	- Pour faire des routes, des marquages et des passage pietons tout joli!
	- [x] TESTED
	- [x] WANTED
	- [x] ENDGAME
	- SeeAlso: https://mods.factorio.com/mods/Tone/More_Floors

## Améliore l'usage des véhicules (et tourelles)

- https://mods.factorio.com/mod/justgo
	- Lorsqu'on place un vehicule = On entre automatiquement dedans!
	- [x] TESTED : ne fait rien = ne marche ?!
	- [x] BUG
	- [ ] WANTED
	- license: MIT

- Fill4me : https://mods.factorio.com/mod/Fill4Me
	- [x] TESTED (pour l'auto fuel, mais l'auto munition est sympa aussi!)
	- [x] WANTED
	- charge du fuel dans un vehicule automatiquement (je veux!), ne s'applique pas aux tourelles placés par les drones.
	- charge des munitions automatiquement dans une tourelle (est-ce qu'on veut ?)
	- license: BSD-3-Clause

- Ammo Loader+ : https://mods.factorio.com/mod/ammo-loader
	- charge des fuel/munition auto => un peu trop automatisé ?
	- [ ] TESTED
	- license: GNU GPLv3
	- not-tested

## Ajout de véhicules

- Hovercrafts : https://mods.factorio.com/mod/Hovercrafts
	- allons sur l'eau! trop bien!!! en + il est très sympa sur la terre aussi!
	- license: CC BY-SA 4.0
	- [x] TESTED
	- [x] WANTED
	- [x] TESTED bug avec electric-vehicle-lib-reborn (et LaserTank)
	- https://mods.factorio.com/mod/Hovercrafts/discussion/5cc9c7712ff750000d6dbc2f

- Cargo Ships : https://mods.factorio.com/mod/cargo-ships
	- après les trains, des bateaux!
	- [ ] TESTED
	- license:


## Téléportateur

- [x] https://github.com/Klonan/Teleporters
	- Construire des téléporteurs pour les joueurs pour se déplacer de base en base
        - Teleporteur de base en base
        - [x] partial-TESTED (necessite la recherche)
	- license:
        - bon compromis/alternative à "Portals" ?

- [~] https://mods.factorio.com/mod/Portals
	- Un portalgun et une paire de portail orange et bleu pour chaque joueur! Mais où est GLaDOS ?!
	- license: GNU GPLv3
	- [x] TESTED : portal-gun, limon grenade
	- [x] WANTED (parce que bug fixed)
	- Des portalgun (et des grenades citron!)
	- Bug corrigé: il permettait de poser le portail bleu n'importe où (meme dans les zone non explorée) ca venait visiblement d'un bug de factorio (corrigé en 0.17.35)
	- On peut poser un portail a distance partout où on a la vision
	- On peut changer les réglages et choisir de n'autoriser que les portails proches du joueur (ca n'empeche pas d'en poser 2 avec une très grande distance entre les 2)
	- https://mods.factorio.com/mod/Portals/discussion/5cc9ccb42ff750000b3952f4


# terre/eau/pont

* [x] Beautiful Bridge Railway : https://mods.factorio.com/mod/beautiful_bridge_railway
	- Des ponts!
	- license: MIT
	- [x] TESTED
	- [x] WANTED
	- But: remplacer le ramblai par des ponts
	- de ce que j'ai testé ils ne sont utilisable que par les trains

* [ ] Expensive Landfill Recipe : https://mods.factorio.com/mod/ExpensiveLandfillRecipe
	- Augmentant le prix du ramblai (ca force utiliser des ponts à la place!)
	- license: MIT
	- [ ] tested
	- Note: il n'est peut-être pas utile d'augmenter son prix pour ne pas l'utiliser

# INTERFACE / AIDE

* https://mods.factorio.com/mod/RadarGridGuide
	- Aide a placer les radar régulièrement pour avoir une meilleur couverture
	- license:
	- [ ] tested

- https://mods.factorio.com/mod/ShowUnconnected
	- indication des éléments non connectés (ca montre des loupés et des bugs, dans notre partie existante ;-))
	- license: MIT
	- [x] TESTED
	- [x] WANTED
	- [x] Feature Requested : https://mods.factorio.com/mod/ShowUnconnected/discussion/5cc9d48c2ff750000ca5a210
		- need: pouvoir le desactiver (le rendu), utile mais chiant de voir clignoter des warnings partout.

- https://mods.factorio.com/mod/speaker-signals
	- [ ] TESTED
	- [x] WANTED
	- Plus d'icons !
	- license:

- https://mods.factorio.com/mod/speaker-signals-expansion
	- [ ] TESTED
	- [x] WANTED
	- Encore plus d'icons !
	- license:


# Aide a la construction

- https://mods.factorio.com/mod/GhostInHand
	- [ ] TESTED
	- [ ] WANTED
	- Utile lorsqu'on veut construire uniquement avec des ghost et laisser les drones faire le boulot
	- Inutile: car deja intégré dans les options du jeu 0.17 (a verifier si on a activé l'option)
	- Utile: pour avoir un bouton/racourcis rapide ?
	- license: MIT

- https://mods.factorio.com/mod/power-grid-comb
	- Permet de recabler les fils des réseaux électrique pour un resultat plus carré. Perfectionniste.
	- [ ] TESTED
	- [ ] WANTED
	- license:

-  https://mods.factorio.com/mod/Logistic-Request-Manager
	- ?
	- [ ] TESTED
	- license:

# DU BIO

- Bio Industries : https://mods.factorio.com/mod/Bio_Industries
	- Ajoute des graines, etc. et de quoi recuperer des materiaux sur certains equipements crafté (four, etc) un peu comme "Reverse Factory"
	- license: MIT
	- [x] partial-TESTED: ca a l'air bien (mais ca ouvre bcp de nouvelle possibilité)

- Robot Tree Farm : https://mods.factorio.com/mod/robot_tree_farm
	- Les robots peuvent planter des arbres!
	- [ ] TESTED
	- license: CC BY-SA 4.0

- https://mods.factorio.com/mod/Bioluminescence
	- Ajoute des arbres bioluminescent (ce sont des arbres en + des arbres normaux)
	- [x] TESTED
	- [x] WANTED ?
	- [ ] TESTED MORE ?
	- [x] WARNING: nécessite de regénérer le terrain => attention aux inconvénients/danger !
	- Fonctionne pour une nouvelle partie. (qu'a la création du terrain?)
	- Ne fonctionne pas pour une partie existante ?
	- license: non-free! (Visible Source, No Public Derivatives)

## Outil pour regenerer le terrain

- Regenerate Terrain : https://mods.factorio.com/mod/regenerate-terrain
	Permet de regénérer le terrain
	- [x] TESTED
	- [x] WANTED si besoin, pour Bioluminescence par exemple
	- [x] WARNING: Testé sur la grande partie (ca prend un peu de temps, ca fait respawn les bitters et perdre la vision/exploration) mais ca marche.
	- license: non-free!


# recyclage

- Reverse Factory : https://mods.factorio.com/mod/reverse-factory
	- permet de recycle des objects et recuperer la matiere premiere
	- [ ] TESTED
	- license: MIT


# More FUTURIST


- https://mods.factorio.com/mod/aai-vehicles-laser-tank
	- un tank qui est vraiment classe !
	- [x] TESTED
	- [x] WANTED
	- license: non-free!

- https://mods.factorio.com/mod/laser_tanks
	- Change l'apparence du tir lazer du tank
	- license: CC BY-SA 4.0
	- [x] TESTED
	- [x] BUG!
	- [ ] wanted
	- Le bug vient de la lib "Electric Vehicles Lib: Reborn" mod (le mod laser_tanks inclus la version 0.1.0) (le bug se reproduit sans laser_tank avec uniquement la lib, meme en version 0.1.2)
		- voir: https://mods.factorio.com/mod/Hovercrafts/discussion/5cc9c7712ff750000d6dbc2f

* https://mods.factorio.com/mod/laser_rifle
	- si on a deja un lazer portatif pourquoi pas une arme ? trop cheaté ?
	- [ ] TESTED

## arme trop dangeureuse ?

- https://mods.factorio.com/mod/railgun_enhancer
- https://mods.factorio.com/mod/railgun_revival


# New tiles

- Dectorio : https://mods.factorio.com/mod/Dectorio
	- decorative elements
	- [ ] TESTED
	- [x] WANTED

- https://mods.factorio.com/mod/InlaidLampsExtended
	- [ ] TESTED
	- [x] WANTED

# ARMEMENT

- https://mods.factorio.com/mod/Turret-Shields
	- game def
	- [ ] TESTED
	- [ ] WANTED
	- license: ?

- https://mods.factorio.com/mod/uniturret
	- Des tourelles universelles
	- [ ] TESTED
	- [ ] WANTED
	- license: ?



## cosmetic

- https://mods.factorio.com/mod/MushroomCloud
	- [ ] TESTED

- [ ] https://mods.factorio.com/mod/bullet-trails
	- Cosmetic, balle tracante
	- license: non-free!

- https://mods.factorio.com/mod/Concretexturex
	- [ ] TESTED




# organisation

- helmod :
	-
	- [x] TESTED
	- [~] BUG: j'ai eu des problèmes entre helmod, todolist, et dans certains cas de synchro pre-load qui ne se passait pas bien
	- [x] WANTED
	- TODO: helmod -> demander un sample de donnees ?

- Actual Craft Times Remade : https://mods.factorio.com/mod/actual-craft-times-remade
	- [x] TESTED: bug?! ca n'affiche rien la ou ca devrait...
	- [ ] WANTED

 - [ ] https://mods.factorio.com/mod/what-is-it-really-used-for
	-
	-

# Reseau electrique

- https://mods.factorio.com/mod/Transformers
	- Permet de charger des accumulateurs locaux, energie de secours?
	- [ ] TESTED
	- [ ] WANTED
	- license: MIT



# STOCKAGE

* [ ] https://mods.factorio.com/mod/better-storage-tanks
	- des gros coffres (on veut vraiment ?!)
	- [ ] WANTED


# ?

- [ ] https://mods.factorio.com/mod/EvenMoreLights

- [ ] (0.16 only) https://mods.factorio.com/mod/attach-notes
	- Des pancartes!
	-

# Sound/Music

- https://mods.factorio.com/mod/original-music-hd-updated










# Pour moder :

- https://mods.factorio.com/mod/DataRawSerpent


- https://mods.factorio.com/mod/ScorchedEarth
	- la terre est brulée




Tester le jeu avec tous les mods de OwnlyMe ?

- couleur des resources, Reasonable Color ...
- les arbres/sol : https://mods.factorio.com/mod/unlushed_trees
- apparence realiste : https://mods.factorio.com/mod/better_ore_icons


# FUN LOL

- Ball Biters : https://mods.factorio.com/mod/BallBiters
	- Au revoir les cafards, bonjour les balles! #FUN #LOL
	- license: MIT
	- [x] TESTED
	- [x] FUN
	- [ ] WANTED (temporaire pour rigole = oui, pas permanent)


# DELIRANT


- https://mods.factorio.com/mod/reasonable-colours
	- Change la couleur (un peu) des belt/usine/...


- https://mods.factorio.com/mod/lightorio
	- Lumiere



# a voir ...


- https://mods.factorio.com/mod/ZRecycling

- https://mods.factorio.com/mod/belt-brush

- https://mods.factorio.com/mod/artillery-bombardment-remote


# FUN  CRAZY

- https://mods.factorio.com/mod/graftorio
	- grafana+factorio ! CRAZY!
	

# Mort

- https://mods.factorio.com/mod/DeathNotice
	- ...
	- [ ] TESTED
	- [x] BUG: Possible BUG!

- https://mods.factorio.com/mod/infinitycorpeslive (non-free)
	- Cadavre de joueur n'est plus limité dans le temps
	- [ ] TESTED

- https://mods.factorio.com/mod/auto-research
	- ...
	- [ ] TESTED
	- [ ] WANTED

- pas compris : https://mods.factorio.com/mod/pipelayer

- Lua prog : https://mods.factorio.com/mods/tesseractcat/scriptable-drones




- https://mods.factorio.com/mod/secondary-chat


- https://mods.factorio.com/mod/QoL-TempStations

- https://mods.factorio.com/mod/Shortcuts
	-> voir les boutons pour deplacer, il faudrait la meme chose dans helmod

- https://mods.factorio.com/mod/TrainSkipFulfilledStation
- https://mods.factorio.com/mod/Automatic_Train_Painter

- https://mods.factorio.com/mod/aai-zones

- Modding : https://mods.factorio.com/mod/YouModRecipe

- https://mods.factorio.com/mod/building-platform

