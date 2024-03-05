# KiCad 8.0 PKGBUILD

This is a fork of git@github.com:cbrake/arch-kicad-8.git that can be used to
build and install KiCad 8.0 on Arch Linux.

## Install

- `git clone https://github.com/cbrake/arch-kicad-8.git`
- `cd arch-kicad-8`
- `makepkg`
- `sudo pacman -U kicad-nightly-8.0.0_0_g942661fc10-1-x86_64.pkg.tar.zst`
- `yay kicad-library-nightly`
- `yay kicad-library-3d-nightly`

And you should be off an running ...

This installs in parallel with KiCad 7.0 so you can run both if needed.

You can also download a pre-built KiCad binary from:

https://files.bec-systems.com/kicad/
