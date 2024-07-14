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
- Rajouter les options de lancement suivantes sur **Steam** :
  - Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
  - Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`
- Télécharger le [**pack de configurations additionnelles** (lien cliquable)](https://github.com/nbusseneau/lotus-ecarlate-valheim-modpack/releases/latest/download/pack_configs_additionnelles.zip) puis l'installer :
  - Accéder aux fichiers du profil depuis **r2modman** avec `Settings` > `Browse profile folder`
  - Naviguer dans le dossier `BepInEx` > `config` et y extraire tous les fichiers `.cfg` du pack (écraser / remplacer en cas de conflit avec les fichiers existants)
  - ⚠️ Tous les fichiers `.cfg` extraits doivent être dans `config`, pas dans un sous-dossier de `config`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs.
Il faut toujours lancer depuis **r2modman** :

- `Valheim` > `Select game` > `Steam` > `Select platform` > sélectionner le bon profil > `Select profile` > `Start modded`
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y a un message en haut à gauche `Running BepInEx - X plugins loaded` 😉

Lors du premier lancement, modifier les raccourcis clavier suivants dans `Paramètres` > `Clavier et souris` :

- `S'asseoir` : changer de `X` vers `Y`
- `Activer/Désactiver Marche` : changer de `C` vers `U`

(nécessaire pour éviter des conflits avec des raccourcis utilisés par des mods du pack)

## Mises à jour

### **⚠️ Ne cliquez jamais sur la bannière `Update all`** qui s'affichera en haut de la liste des mods sur **r2modman**, sinon vous risquez d'installer des versions incompatibles des mods.

Les seules mises à jour à faire sont celles du pack **Lotus Ecarlate** lui-même (il se chargera de mettre à jour les autres mods) :

- `Installed` > taper `Lotus` en recherche > `Lotus Ecarlate` > `Update` > `Download with dependencies`

Chaque mise à jour sera annoncée pour que vous soyez au courant 😉
