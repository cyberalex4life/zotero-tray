# zotero-tray
## A script that starts and iconifies Zotero using kdocker and xdotool.

### Requierements
- zotero executable (placed in PATH)
- kdocker
- xdotool 

Please place this script in a location form PATH environment variable and make it executable (`/usr/bin`; `/usr/local/bin`; `~/bin`):

##### $ sudo chmod +x \[zotero-tray path\]/zotero-tray

In `zotero.desktop` (wherever that is: `/usr/share/applications/`; `/usr/local/share/applications/`; `~/.local/share/applications/`) change `Exec=zotero` line to `Exec=zotero-tray`.

Be sure that `Iconify when minimized` is checked in the options of the tray icon, so that you can also hide zotero running this script, or using the modified launcher.

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
