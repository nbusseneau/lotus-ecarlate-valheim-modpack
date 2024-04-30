# Lotus Écarlate

Custom Thunderstore modpack for Lotus Écarlate's private Valheim server. Nothing
to see here, move along citizen!

## Installation

- Télécharger et installer [**r2modman** (lien cliquable)](https://thunderstore.io/c/valheim/p/ebkr/r2modman/). Instructions détaillées :
  - `Manual Download` > extraire zip > installer `r2modman Setup X.X.X.exe`
- Lancer **r2modman** et sélectionner le jeu **Valheim**
  - `Valheim` > `Select game` > `Steam` > `Select platform`
- Sélectionner le profil **Default**
  - `Default` > `Select profile`
- Installer le pack **Lotus Ecarlate**
  - `Online` > chercher `Lotus` > `Lotus Ecarlate` > `Download` > `Download dependencies`

## Lancer le jeu avec les mods

Si vous lancez le jeu depuis Steam, les mods ne seront pas actifs.
Il faut toujours lancer depuis **r2modman** :

- `Valheim` > `Select game` > `Steam` > `Select platform` > `Default` > `Select profile` > `Start modded`
- Si vous avez tout bien fait, au lancement du jeu il y a une console qui s'ouvre, et sur le menu principal il y a un message en haut à gauche `Running BepInEx - X plugins loaded` 😉

## Configuration

### Paramètres de lancement Steam

Afin d'optimiser les performances, rajouter les options de lancement suivantes sur **Steam** :

- Clic droit sur `Valheim` dans la bibliothèque > `Propriétés` > `Options de lancement`
- Copier/coller `-gfx-enable-gfx-jobs -gfx-enable-native-gfx-jobs`

### Raccourcis claviers

Les mods rajoutent de nouveaux raccourcis claviers, et il y a un conflit avec les touches par défaut `W`/`X`.
Modifier les paramètres raccourcis clavier suivants dans les paramètres du jeu :

- La touche utilisée pour passer en vitesse de marche, par défaut sur `W`. Suggestion : `U`.
- La touche utilisée pour s'asseoir, par défaut sur `X`. Suggestion : `Y`.

## Mises à jour

Lorsque des mises à jour sont disponibles, une bannière `Update all` s'affichera en haut de la liste des mods sur **r2modman** :

- **⚠️ Ne faites pas les mises à jour des mods vous-mêmes, ne cliquez pas sur la bannière `Update all`.**
- Si vous le faites alors que le serveur dédié n'a pas encore été mis à jour, vous risquez de ne pas pouvoir rejoindre le serveur.

Deux scénarios où une mise à jour sera nécessaire :

- Le serveur dédié a été mis à jour et vous refuse la connexion.
- Si j'annonce qu'une mise à jour est nécessaire... 😁

Dans ces cas-là, mettez à jour **uniquement** le pack **Lotus Ecarlate** lui-même :

- `Installed` > `Lotus Ecarlate` > `Update` > `Download with dependencies`
