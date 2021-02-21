# Maintainer: Nick Harder <nickharder88@gmail.com>

pkgname=xrandr-autoscale
pkgrel=1
pkgver=1
pkgdesc="Auto scale with xrandr"
arch=("x86_64")
url="https://github.com/nickharder88/autoscale"
license=("GPL")
md5sums=()
depends=(xorg-xrandr)
makedepends=()
provides=("xrandr-autoscale")
conflicts=("xrandr-autoscale")

package() {
  install -Dm755 "autoscale.sh" "$pkgdir/usr/local/sbin/autoscale.sh"
  install -Dm644 "autoscale.service" "$pkgdir/usr/lib/systemd/user/autoscale.service"
}