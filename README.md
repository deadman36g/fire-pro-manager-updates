# Fire Pro Wrestling World Manager updates

This public repository hosts the update manifest and Windows installer releases used by the app's in-app updater.

- `manifest.json` lists the current installer version and its SHA-256 checksum.
- Tagged GitHub Releases contain the downloadable Windows installer.
- Application source code remains in its separate private repository.

The app verifies the downloaded installer against the checksum in `manifest.json` before offering it for installation.