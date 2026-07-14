# FF8 Android Save Editor — application mobile v0.1

Application Android native permettant de modifier directement une sauvegarde
de **Final Fantasy VIII Remastered** sur téléphone.

## Fonctionnement

1. Copier le fichier `.ff8` du dossier du jeu vers `Documents` ou `Téléchargements`.
2. Ouvrir ce fichier dans l’application.
3. Cocher les options souhaitées.
4. Exporter la nouvelle sauvegarde.
5. La recopier dans le dossier `savedata/slotXXX`.

L’application utilise le sélecteur de fichiers Android :
elle ne demande pas l’accès général au stockage et ne modifie jamais le fichier
source.

## Options

- Profil Ultimate complet
- 1 000 000 Gils
- 16 G-Forces
- Magies optimisées ×100
- Inventaire Ultimate ×99
- Réapprovisionnement des objets
- 110 cartes Triple Triad
- Rang SeeD A
- Open dans les 8 régions

## Construire l’APK avec GitHub

1. Déposer ce projet à la racine d’un dépôt GitHub.
2. Ouvrir l’onglet **Actions**.
3. Lancer **Build Android APK**.
4. Télécharger l’artefact `FF8AndroidSaveEditor-Android`.

## Construire avec Android Studio

Ouvrir le dossier dans Android Studio, attendre la synchronisation Gradle,
puis choisir **Build > Build APK(s)**.

## Limitation Android

Android protège le dossier privé des autres applications dans `Android/data`.
Selon le gestionnaire de fichiers utilisé, il peut être nécessaire de copier
manuellement la sauvegarde vers un dossier accessible avant de l’ouvrir, puis
de la recopier dans le dossier du jeu après modification.
