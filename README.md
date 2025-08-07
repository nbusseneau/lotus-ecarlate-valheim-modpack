# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's private Valheim server. Nothing
to see here, move along citizen!

## Installation

- Télécharger et installer [**Gale** (lien cliquable)](https://kesomannen.com/gale). Instructions détaillées :
  - `Download` > `.msi installer` > installer `Gale_X.Y.Z_x64_en-US.msi`
- Lancer **Gale** et sélectionner le jeu **Valheim**
- Si vous aviez déjà **r2modman**, **Gale** vous proposera d'importer vos profils : si vous voulez migrer sur **Gale** (cémieux que **r2modman**), allez-y, mais pour le serveur il faudra utiliser un profil vierge de toutes façons.
- Créer un nouveau profil vierge (ou utiliser le profil **Default** s'il est vierge)
  - `Profile` > `Create new profile` > taper un nom de profil > `Create`
- Installer le pack **Lotus Ecarlate** (ignorer le mod **Lotus Ecarlate Changes**, c'est une sous-partie du pack)
  - 2e onglet sur la gauche > taper `Lotus` en recherche > `Lotus Ecarlate` > `Install`
  - **⚠️ Important : ne jamais cliquer sur la bannière `Update all`** qui s'affichera en haut de la liste des mods (1er onglet) après installation du pack
- Télécharger le [**pack de configurations additionnelles** (lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/pack_configs_additionnelles.zip) puis l'installer :
  - Accéder aux fichiers du profil depuis **Gale** avec `File` > `Open profile folder`
  - Naviguer dans le dossier `BepInEx` > `config` et y extraire tous les fichiers `.cfg` du pack (écraser / remplacer en cas de conflit avec les fichiers existants)
  - ⚠️ Tous les fichiers `.cfg` extraits doivent être dans `config`, pas dans un sous-dossier de `config`
- Rajouter les options de lancement suivantes sur **Steam** :
  - Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
  - Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs :

- Il faut toujours lancer depuis **Gale** avec le bouton `Launch game` en haut à gauche (assurez-vous de sélectionner le bon profil si vous en avez plusieurs).
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur l'écran principal il y a un nouveau menu `Mods settings` en plus d'un message en bas à droite `You are playing a modded version of Valheim` 😉

Lors du premier lancement, modifier les paramètres suivants dans `Settings` (`Paramètres`) :

- Il est fortement conseillé de mettre le jeu en anglais dans l'onglet `Gameplay`. C'est jouable en français si vous y tenez, mais une partie des mods n'est pas traduite et de toutes façons la traduction du jeu de base est plutôt nulle, donc ça casse un peu l'immersion.
- Modifier les raccourcis clavier suivants dans `Keyboard & Mouse` (`Clavier et souris`) pour éviter des conflits avec des raccourcis utilisés par des mods du pack :
  - `Toggle walk` (`Activer/Désactiver Marche`) : changer de `C` vers `U`
  - `Sit` (`S'asseoir`) : changer de `X` vers `Y`

Autres paramètres probablement importants à bidouiller (pas forcément dès le premier lancement, vous pouvez changer ça plus tard) :

- Si vous souhaitez que le **Sprint (Shift)** soit un toggle et pas un maintien :
  - `Settings` (`Paramètres`) > `Accessibility` (`Accessibilité`) > `Auto-run` (`Course automatique`). Non, ce label n'a aucun sens 🙄
- Si vous souhaitez modifier les raccourcis clavier pour les emplacements d'inventaire supplémentaires :
  - `F1` > `Extra Slots` > `Hotkeys` > ajuster `Ammo`, `Food`, et `Quickslots` (1 à 3, les slots 4 à 6 ne sont pas actifs)
  - N'oubliez pas de modifier également le texte affiché dans l'inventaire, en plus du raccourci clavier.

## Mises à jour

### **⚠️ Ne jamais cliquer sur la bannière `Update all`** qui s'affichera en haut de la liste des mods (1er onglet), sinon vous risquez d'installer des versions incompatibles des mods.

Les seules mises à jour à faire sont celles du pack **Lotus Ecarlate** lui-même :

- 1er onglet sur la gauche > taper `Lotus` en recherche > `Lotus Ecarlate` > `Update`

Les mises à jour seront annoncées sur Discord 😉
