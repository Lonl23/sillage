# Sillage

Canal d’installation de l’application Android. Ce dépôt ne contient aucune donnée de santé.

L’application installée consulte `releases/latest.json` à l’ouverture. Si `versionCode` est plus grand que la version installée, elle télécharge les morceaux dans `releases/parts`, vérifie l’empreinte, puis ouvre l’installeur Android.

La première installation se fait avec le fichier `sillage.apk` fourni avec le projet. Les mises à jour suivantes arrivent par ce dépôt, avec la même signature.
