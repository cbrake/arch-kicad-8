# KiCad 8.0 PKGBUILD

This is a fork of git@github.com:cbrake/arch-kicad-8.git that can be used to
build and install KiCad 8.0 on Arch Linux.

## Install KiCad 8 application from source

- `git clone https://github.com/cbrake/arch-kicad-8.git`
- `cd arch-kicad-8`
- `makepkg`
- `sudo pacman -U kicad-nightly-8.0.0_0_g942661fc10-1-x86_64.pkg.tar.zst`

This installs in parallel with KiCad 7.0 so you can run both if needed.

## Install pre-built binary

https://files.bec-systems.com/kicad/

## Install libraries

- `yay kicad-library-nightly`
- `yay kicad-library-3d-nightly`
