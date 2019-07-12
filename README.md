# io.dbeaver.DBeaverCommunity.Client.pgsql

Extension to provide extended support (e.g. backup/restore) for PostgreSQL to the flatpaked version of DBeaver. You can install DBeaver from Flathub https://flathub.org/apps/details/io.dbeaver.DBeaverCommunity.

This extension only contains stripped client binaries.

## Build
```bash
flatpak-builder --repo repo build-dir io.dbeaver.DBeaverCommunity.Client.pgsql.json --force-clean
```
Add `--default-branch=stable` to build against the Flathub version of DBeaver.
