 
# Arch PKGBUILDs


Collection of PKGBUILDs I maintain for the [AUR](https://aur.archlinux.org).


## Updating

Update `pkgver` in PKGBUILD to the latest release version.

Generate new checksums using `updpkgsums` from the `pacman-contrib` package if applicable.

```sh
updpkgsums
```

## Publishing

Standard git workflow applies here. See the [Arch Wiki](https://wiki.archlinux.org/title/AUR_submission_guidelines).

## Contributing

Please Open a Pull Request or an Issue. If I have not responded in awhile, feel free to suggest co-maintainer or orphaning the package.

## Packages

### EmuDeck

Builds [EmuDeck](https://emudeck.com) from the latest stable release, for setup of emulation.

Link: https://aur.archlinux.org/packages/emudeck

### SkyEmu (git) 

Builds [SkyEmu](https://github.com/skylersaleh/SkyEmu) from the latest git release, for emulation of GBA, GBC, and GB games.

Link: https://aur.archlinux.org/packages/skyemu-git

### upset (CLI)

Builds [upset](https://github.com/cosarara/upset), a fork of [Near's UPS patching tool](https://www.romhacking.net/utilities/677/) designed for use via the CLI. This is primarily used for ROM hacking retro games.

Link: https://aur.archlinux.org/packages/upset_cli

## Installing

You can use an AUR wrapper like [paru](https://github.com/Morganamilo/paru):

```sh
paru -S <package_name>
```

## Building

Build with makepkg

```sh
makepkg -fc
```

Check more information on the [Archwiki](https://wiki.archlinux.org/index.php/Makepkg)

## Maintainer

 [Griffin](https://github.com/WingofaGriffin)

