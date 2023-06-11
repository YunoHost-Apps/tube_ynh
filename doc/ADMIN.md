#### Where are stored your videos

Your video files are stored by default in `__DATA_DIR__/videos`.

You can configure options in this file `__INSTALL_DIR__/config.json` using the [documentation](https://git.mills.io/prologic/tube#configuration). Remember to restart Tube service if you change your configuration file.

RSS feed address is available at `https://__DOMAIN__/feed.xml`

The data directory with uploaded videos is untouched when upgrading the app. If you want to delete the data directory with the application, use the `--purge` option: `sudo yunohost app remove tube --purge`

