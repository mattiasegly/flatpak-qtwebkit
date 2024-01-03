# flatpak-qtwebkit
<BR>Flatpak builds of Qt WebKit from git https://github.com/movableink/webkit as base for QGIS.
<BR>This is a test/staging area, so it's very experimental and might not work.
<BR>
<BR>Build:
<BR>clear && flatpak-builder --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir io.qt.qtwebkit.BaseApp
<BR>
<BR>Build & Install:
<BR>clear && flatpak-builder --user --install --jobs=3 --ccache --disable-rofiles-fuse --force-clean build-dir io.qt.qtwebkit.BaseApp
<BR>
<BR>Or download an artifact from https://github.com/mattiasegly/flatpak-qtwebkit/actions/workflows/flatpak-builder.yml
<BR>Extract .zip archive and install with:
<BR>flatpak --user install qtwebkit.flatpak
