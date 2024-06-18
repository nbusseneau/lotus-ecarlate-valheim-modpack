# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's private Valheim server. Nothing
to see here, move along citizen!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/valheim/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer `r2modman Setup X.X.X.exe`
- Lancer **r2modman** et sélectionner le jeu **Valheim**
  - `Valheim` > `Select game` > `Steam` > `Select platform`
- Sélectionner le profil **Default** (ou en créer un nouveau)
  - `Default` > `Select profile`
- Installer le pack **Lotus Ecarlate**
  - `Online` > chercher `Lotus` > `Lotus Ecarlate` > `Download` > `Download dependencies`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs.
Il faut toujours lancer depuis **r2modman** :

- `Valheim` > `Select game` > `Steam` > `Select platform` > `Default` > `Select profile` > `Start modded`
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y a un message en haut à gauche `Running BepInEx - X plugins loaded` 😉

## Configuration

À faire une seule fois, lors de la première installation :

### Paramètres de lancement Steam

Afin d'optimiser les performances, rajouter les options de lancement suivantes sur **Steam** :

- Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
- Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`

### Pack de configurations additionnelles

Afin d'éviter que certaines de vos configurations locales (notamment raccourcis claviers) ne soient écrasées à chaque mise à jour du pack, une partie des configurations doit être installée manuellement :

- Télécharger le [**pack de configurations additionnelles** (lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/pack_configs_additionnelles.zip)
- Accéder aux fichiers du profil depuis **r2modman**
  - `Settings` > `Browse profile folder`
- Extraire le contenu du pack dans le profil. À la fin, ça doit ressembler à ça :
  ```
  nom-profil-r2modman/
  ├── BepInEx/
  │   └── config/
  │       ├── config.toto.cfg
  │       ├── config.tata.cfg
  │       └── ...
  ├── mods.yml
  └── (s'il ne s'agissait pas d'un profil vierge : il y aura également d'autres dossiers et fichiers en plus)
  ```

### Raccourcis claviers

Les mods rajoutent de nouveaux raccourcis claviers, et il y a un conflit avec les touches par défaut de Valheim.
Modifier les paramètres raccourcis clavier suivants dans les paramètres du jeu :

- `X`, qui est par défaut la touche utilisée pour s'asseoir (avec les mods, s'asseoir a désormais une vraie utilité, c'est pas que pour le style)
  - Recommandé à la place : `Y`
- `W`, qui est par défaut la touche utilisée pour passer en vitesse de marche (ça par contre ça n'a toujours aucune utilité)
  - Recommandé à la place : `U`

Si vous souhaitez modifier les raccourcis claviers utilisés pour des mods, vous pouvez le faire en jeu depuis le menu accessible via `Échap` > `Mods settings` (ou `F1`), puis en activant uniquement le filtre `Keybinds`.

### Mods optionnels

Ces mods ne sont pas intégrés au pack par défaut car ils sont complexes à prendre en main, mais ils peuvent être intéressants faire des constructions avancées et très précises. Ces mods ne sont pas recommandés aux débutants ni à ceux qui n'ont pas l'intention de se concentrer sur les contructions.

⚠️ Il faudra que vous preniez le temps de configurer les touches, car avec celles par défaut il y aura des conflits avec d'autres mods du pack. Des configurations avec touches compatibles sont disponibles [ici](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/tree/main/optionalClientConfig/), à installer manuellement si vous souhaitez les essayer.

- [Gizmo](https://thunderstore.io/c/valheim/p/ComfyMods/Gizmo/)
  - Permet de faire tourner les pièces sur n'importe quel axe et avec n'importe quel incrément (alors que de base, c'est uniquement sur l'axe Y, par incréments de 45°).
- [Extra Snap Points Made Easy](https://thunderstore.io/c/valheim/p/Searica/Extra_Snap_Points_Made_Easy/)
  - Rajoute des points d'accroche supplémentaires sur les pièces, par exemple au centre d'un mur (de base : uniquement dans les coins) ou sur les coffres (de base : y en a pas, les coffres ne s'accrochent jamais)
  - Permet d'accrocher les pièces sur les points d'accroche d'une pièce déjà posée (de base : seuls les points d'accroche de la pièce en cours de pose sont utilisables)
  - Permet d'accrocher les pièces sur une grille virtuelle pour pouvoir tout aligner tout beau tout propre, avec maillage configurable

## Mises à jour

Lorsque des mises à jour sont disponibles, une bannière `Update all` s'affichera en haut de la liste des mods sur **r2modman** :

- **⚠️ Ne cliquez jamais sur la bannière `Update all`**
- Si vous le faites alors que le serveur dédié n'a pas les versions correspondantes des mods, vous risquez de ne pas pouvoir rejoindre le serveur (ou pire : réussir à rejoindre mais avoir des truc pétés, et ça peut être traître et ne même pas forcément se voir immédiatement)

Les seules mises à jour à effectuer sont celles du pack **Lotus Ecarlate** lui-même :

- `Installed` > `Lotus Ecarlate` > `Update` > `Download with dependencies`

Chaque mise à jour sera annoncée pour que vous soyez au courant 😉

### Exception

- Si vous avez installé des mods optionnels (comme indiqué ci-dessus), alors bien sûr vous pouvez les mettre à jour 😎
