# Guide ultra simple — créer l’APK avec GitHub depuis un téléphone

## Ce fichier ZIP est prêt à être envoyé sur GitHub

Tu n’as pas besoin de modifier le code.

## Étapes

1. Crée un compte sur GitHub.
2. Crée un nouveau dépôt nommé :
   `FF8-Android-Save-Editor`
3. Décompresse ce ZIP sur ton téléphone.
4. Envoie **tout le contenu décompressé** dans le dépôt GitHub.
   Important : les fichiers `settings.gradle`, `build.gradle` et le dossier `app`
   doivent être directement à la racine du dépôt.
5. Ouvre l’onglet **Actions** du dépôt.
6. Sélectionne **Build Android APK**.
7. Appuie sur **Run workflow**.
8. Attends que le travail soit terminé avec une coche verte.
9. Ouvre le résultat puis télécharge l’artefact :
   `FF8AndroidSaveEditor-Android`
10. Décompresse l’artefact et installe le fichier APK.

## Si Android bloque l’installation

Autorise temporairement l’installation d’applications inconnues pour
l’application utilisée pour ouvrir l’APK, puis relance l’installation.

## Important

Le ZIP contient le code source, pas directement l’APK.
GitHub fabrique l’APK automatiquement grâce au fichier :

`.github/workflows/build-android.yml`
