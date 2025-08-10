# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's private Valheim server. Nothing
to see here, move along citizen!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/valheim/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer `r2modman Setup X.Y.Z.exe`
- Lancer **r2modman** et sélectionner le jeu **Valheim**
  - `Valheim` > passer le jeu en favori en cliquant sur la petite étoile > `Select game` > `Steam` > `Select platform`
- Créer un nouveau profil vierge et le sélectionner (ou utiliser le profil **Default** s'il est vierge)
  - `Create new` > taper un nom de profil > `Select profile`
- Installer le pack **Lotus Ecarlate** (ignorer le mod **Lotus Ecarlate Changes**, c'est une sous-partie du pack)
  - `Online` > taper `Lotus` en recherche > `Lotus Ecarlate` > `Download` > `Download dependencies`
  - **⚠️ Important : ne jamais cliquer sur la bannière `Update all`** qui s'affichera en haut de la liste des mods (onglet `Installed`), sinon vous risquez d'installer des versions incompatibles des mods.
- Télécharger le [**pack de configurations additionnelles** (lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/pack_configs_additionnelles.zip) puis l'installer :
  - Accéder aux fichiers du profil depuis **r2modman** avec `Settings` > `Browse profile folder`
  - Naviguer dans le dossier `BepInEx` > `config` et y extraire tous les fichiers `.cfg` du pack (écraser / remplacer en cas de conflit avec les fichiers existants)
  - ⚠️ Tous les fichiers `.cfg` extraits doivent être dans `config`, pas dans un sous-dossier de `config`
- Rajouter les options de lancement suivantes sur **Steam** :
  - Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
  - Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs :

- Il faut toujours lancer depuis **r2modman** avec le bouton `Start modded` en haut à gauche :
  - `Valheim` > `Select game` > `Steam` > `Select platform` > sélectionner le bon profil > `Select profile` > `Start modded`
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

### **⚠️ Ne jamais cliquer sur la bannière `Update all`** qui s'affichera en haut de la liste des mods (onglet `Installed`), sinon vous risquez d'installer des versions incompatibles des mods.

Les seules mises à jour à faire seront annoncées sur Discord, et sont celles du pack **Lotus Ecarlate** lui-même :

- `Installed` > taper `Lotus` en recherche > `Lotus Ecarlate` > `Update` > `Download with dependencies`
