# Maintainer : Yamada Hayao <development@fascode.net>
# Maintainer : lap1sid <development@fascode.net>

pkgname=alterlinux-keyring
pkgver=20200307
pkgrel=1
pkgdesc='AlterLinux PGP keyring'
arch=('any')
url='https:/fascode.net'
license=('GPL')
install="${pkgname}.install"
source=("git:https://github.com/SereneTeam/alterlinux-keyring.git")
sha256sums=('SKIP')
package() {
    cd "${srcdir}"
    make PREFIX=/usr DESTDIR=${pkgdir} install
}