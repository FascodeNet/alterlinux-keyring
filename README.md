# About
GnuPG Keyrings for AlterLinux.

## How to building a package

#### 1. Import GPG key
```bash
gpg --keyserver keyserver.ubuntu.com --recv-key F50544048389DA36
```

#### 2. Clone PKGBUILD repository
```bash
git clone https://github.com/SereneTeam/alterlinux-pkgbuilds.git
```

#### 3. Build
```bash
cd alterlinux-pkgbuilds/stable/alterlinux-keyring
makepkg -s
```

#### Option: Install
```bash
sudo pacman -U alterlinux-keyring*.pkg.tar*
```
