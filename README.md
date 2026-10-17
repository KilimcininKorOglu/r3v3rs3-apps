# r3v3rs3-apps

The catalogs of the r3v3rs3 deployment platform:

- `app-store.json`: the one-click app catalog of the App Store page.
- `engines.json`: the database engines that the Databases page installs.

The r3v3rs3 server embeds a default copy of both files and refreshes them from this
repository once a day over `raw.githubusercontent.com`. Change a file here, push, and the
servers pick it up at their next daily refresh or on the refresh button of the panel.
