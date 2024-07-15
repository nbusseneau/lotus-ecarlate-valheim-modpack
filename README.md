# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's private Valheim server. Nothing
to see here, move along citizen!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/valheim/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer `r2modman Setup X.X.X.exe`
- Lancer **r2modman** et sélectionner le jeu **Valheim**
  - `Valheim` > `Select game` > `Steam` > `Select platform`
- Créer un nouveau profil vierge et le sélectionner (si vous venez d'installer **r2modman**, le profil **Default** suffira)
  - `Create new` > taper un nom de profil > `Select profile`
- Installer le pack **Lotus Ecarlate** (ignorer le mod **Lotus Ecarlate Changes**, c'est une sous-partie du pack)
  - `Online` > taper `Lotus` en recherche > `Lotus Ecarlate` > `Download` > `Download dependencies`
  - **⚠️ Important : ne cliquez jamais sur la bannière `Update all`** qui s'affichera en haut de la liste des mods sur **r2modman** après installation du pack
- Télécharger manuellement [**Toggle Movement Mod**(lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/GetOffMyLawn-ToggleMovementMod-1.2.0.zip) puis l'installer :
  - Depuis **r2modman** > `Settings` > taper `import` en recherche > `Import local mod` > `Select file` > sélectionner le mod téléchargé > `Import local mod`
- Télécharger le [**pack de configurations additionnelles** (lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/pack_configs_additionnelles.zip) puis l'installer :
  - Accéder aux fichiers du profil depuis **r2modman** avec `Settings` > `Browse profile folder`
  - Naviguer dans le dossier `BepInEx` > `config` et y extraire tous les fichiers `.cfg` du pack (écraser / remplacer en cas de conflit avec les fichiers existants)
  - ⚠️ Tous les fichiers `.cfg` extraits doivent être dans `config`, pas dans un sous-dossier de `config`
- Rajouter les options de lancement suivantes sur **Steam** :
  - Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
  - Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs.
Il faut toujours lancer depuis **r2modman** :

- `Valheim` > `Select game` > `Steam` > `Select platform` > sélectionner le bon profil > `Select profile` > `Start modded`
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y a un message en haut à gauche `Running BepInEx - X plugins loaded` 😉

Lors du premier lancement :

- Modifier les raccourcis clavier suivants dans `Paramètres` (`Settings`) > `Clavier et souris` (`Keyboard & Mouse`) pour éviter des conflits avec des raccourcis utilisés par des mods du pack :
  - `Activer/Désactiver Marche` (`Toggle walk`) : changer de `C` vers `U`
  - `S'asseoir` (`Sit`) : changer de `X` vers `Y`
- Si vous souhaitez que le **Sprint (Shift)** soit un toggle et pas un maintien :
  - `F1` > trouver `Valheim - Toggle Movement Mod` et l'ouvrir > cocher `SprintToggle` (passe de `Disabled` à `Enabled`)
  - `Paramètres` (`Settings`) > décocher `Course automatique` (`Auto-run`) > `OK` (sinon il y a conflit avec le toggle du jeu de base)

## Mises à jour

### **⚠️ Ne cliquez jamais sur la bannière `Update all`** qui s'affichera en haut de la liste des mods sur **r2modman**, sinon vous risquez d'installer des versions incompatibles des mods.

Les seules mises à jour à faire sont celles du pack **Lotus Ecarlate** lui-même (il se chargera de mettre à jour les autres mods) :

- `Installed` > taper `Lotus` en recherche > `Lotus Ecarlate` > `Update` > `Download with dependencies`

Chaque mise à jour sera annoncée pour que vous soyez au courant 😉
