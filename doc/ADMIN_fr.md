#### Où sont stockées vos vidéos

Vos fichiers vidéo sont stockés par défaut dans `__DATA_DIR__/videos`.

Vous pouvez configurer les options dans ce fichier `__INSTALL_DIR__/config.json` en utilisant la [documentation](https://git.mills.io/prologic/tube#configuration). N'oubliez pas de redémarrer le service Tube si vous modifiez votre fichier de configuration.

L'adresse du flux RSS est disponible sur `https://__DOMAIN__/feed.xml`

Le répertoire de données avec les vidéos téléchargées n'est pas modifié lors de la mise à niveau de l'application. Si vous souhaitez supprimer le répertoire de données avec l'application, utilisez l'option `--purge` : `sudo yunohost app remove tube --purge`