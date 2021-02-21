# Maintainer: Nick Harder <nickharder88@gmail.com>

pkgname=x11-autoscale
pkgrel=1
pkgver=1
pkgdesc="Auto scale x11 with xrandr"
arch(i686 x86_64)
url="https://github.com/nickharder88/autoscale"
license=('GPL')
md5sums=()
depends=()
makedepends=()
provides=('x11-autoscale')
conflicts=('x11-autoscale')

package() {
  install -Dm755 'autoscale.sh' "$pkgdir/usr/local/sbin/autoscale.sh"
  install -Dm644 'autoscale.service' "$pkgdir/usr/lib/systemd/autoscale.service"
}