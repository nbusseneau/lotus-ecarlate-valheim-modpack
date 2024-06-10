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
- Naviguer vers `BepInEx\config` et y extraire tous les fichiers du pack

### Raccourcis claviers

Les mods rajoutent de nouveaux raccourcis claviers, et il y a un conflit avec les touches par défaut.
Modifier les paramètres raccourcis clavier suivants dans les paramètres du jeu :

- `X`, qui est par défaut la touche utilisée pour s'asseoir (avec les mods, s'asseoir a désormais une vraie utilité, pas que pour le style)
  - Recommandé à la place : `Y`
- `W`, qui est par défaut la touche utilisée pour passer en vitesse de marche (passer en vitesse de marche n'a toujours aucune utilité autre que le style)
  - Recommandé à la place : `U`

Si besoin de modifier des raccourcis claviers pour des mods, vous pouvez le faire en jeu depuis le menu accessible via `Échap` > `Mods settings` (ou `F1`), puis en activant uniquement le filtre `Keybinds`.

### Mods optionnels

Ces mods ne sont pas intégrés au pack par défaut car ils sont un peu complexes à prendre en main, mais ils sont utiles pour ceux qui veulent se concentrer sur la construction :

- [Gizmo](https://thunderstore.io/c/valheim/p/ComfyMods/Gizmo/)
  - Permet de faire tourner les pièces sur n'importe quel axe et avec n'importe quel incrément (alors que de base, c'est uniquement sur l'axe Y, par incréments de 45°)
- [Extra Snap Points Made Easy](https://thunderstore.io/c/valheim/p/Searica/Extra_Snap_Points_Made_Easy/)
  - Rajoute des points d'accroche supplémentaires sur les pièces, par exemple au centre d'un mur (de base : uniquement dans les coins) ou sur les coffres (de base : y en a pas, les coffres ne s'accrochent jamais)
  - Permet d'accrocher les pièces sur les points d'accroche d'une pièce déjà posée (de base : seuls les points d'accroche de la pièce en cours de pose sont utilisables)
  - Permet d'accrocher les pièces sur une grille virtuelle pour pouvoir tout aligner tout beau tout propre, avec incrément configurable

## Mises à jour

Lorsque des mises à jour sont disponibles, une bannière `Update all` s'affichera en haut de la liste des mods sur **r2modman** :

- **⚠️ Ne faites pas les mises à jour des mods vous-mêmes, ne cliquez pas sur la bannière `Update all`**
- Si vous le faites alors que le serveur dédié n'a pas encore été mis à jour, vous risquez de ne pas pouvoir rejoindre le serveur

Deux scénarios où une mise à jour sera nécessaire :

- Le serveur dédié a été mis à jour et vous refuse la connexion
- Si j'annonce qu'une mise à jour est nécessaire... 😁

Dans ces cas-là, mettez à jour **uniquement** le pack **Lotus Ecarlate** lui-même :

- `Installed` > `Lotus Ecarlate` > `Update` > `Download with dependencies`
