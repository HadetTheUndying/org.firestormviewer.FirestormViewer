# org.firestormviewer.FirestormViewer

Unofficial Flatpak wrapper of the Firestorm Viewer for Second Life.

#### Notes

* Enabling voice for the first time will create a wine prefix to run the Windows Vivox voice plugin.

# Build
```bash
git submodule update --init
flatpak --user remote-add --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak-builder --user --install-deps-from=flathub --install _build org.firestormviewer.FirestormViewer.json
```
