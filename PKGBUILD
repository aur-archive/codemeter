# Maintainer: Christian Bühler <christian.buehler@ipoplan.de>
pkgname=codemeter
pkgver=5.0.1057.500
pkgrel=1
pkgdesc="CodeMeter Runtime"
arch=('x86_64')
url="http://www.wibu.com/downloads-user-software.html"
license=('unknown')
source=(${pkgname}64_$pkgver.deb::file://${pkgname}64_$pkgver.deb)
md5sums=('f58052c369b0e8474a914d67a309210c')

package() {
  cd "$pkgdir"
  tar xf "$srcdir/data.tar.gz"
}

# vim:set ts=2 sw=2 et:
