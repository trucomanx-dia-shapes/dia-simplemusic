# dia-simplemusic

![logo](screenshot.png)

## Download

To download, go to the [releases page](https://github.com/trucomanx-dia-shapes/dia-simplemusic/releases).
    
## Manual install/uninstall shapes in the Dia directory

### Install
Manual installation of the package in Dia. Installation is done in the `~/.dia` directory.

    make shapes
    make install

### Uninstall
To uninstall, use:

    make uninstall

Uninstallation is done in the `~/.dia` directory.

### Clean
Finally, if desired, delete the *.shape and *.png files.

    make clean

## Create a release

### Compressed file
Creates a file at `dist/dia-simplemusic-VERSION.tar.gz` where `VERSION` is the current version of the project.

    make dist

### DEB file
Creates a file in `deb/dia-simplemusic-VERSION_all.deb` where `VERSION` is the current version of the project.

    make deb
