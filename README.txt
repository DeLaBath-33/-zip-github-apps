ZIP GitHub - Installation PWA Android

1. Créer un dépôt GitHub distinct, par exemple zip-github-app.
2. Extraire les fichiers de cette archive à la racine de ce dépôt sur la branche main.
3. Dans Settings > Pages : Source = Deploy from a branch, branche main, dossier /(root), puis Save.
4. Ouvrir dans Chrome l’adresse HTTPS : https://VOTRE_COMPTE.github.io/zip-github-app/
5. Menu Chrome (trois points) > Ajouter à l’écran d’accueil ou Installer l’application.
6. Dans l’application, cocher Mémoriser mon token sur cet appareil, puis saisir votre token et vous connecter.

Important : Les données de l’application ne sont pas transférées depuis l’ancien fichier content:// ; il faut saisir une fois le token sur l’adresse HTTPS.
Le token est stocké EN CLAIR dans localStorage pour cette origine HTTPS. Ne pas utiliser sur téléphone partagé et ne pas placer le token dans les fichiers du dépôt.
Le dépôt hébergeant l’app contient seulement du code public, pas le token.
GitHub Pages peut être publiquement accessible selon votre formule et les paramètres du dépôt.
Le navigateur doit garder les données du site pour conserver le token.
