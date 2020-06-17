pkgbase=test-base
pkgname=test
pkgver=0.1
pkgrel=1
pkgdesc='Package test'
url="http://www.test.org/"
arch=(x86_64)
source=(test.sh)
depends=()
makedepends=()
sha256sums=('8275355cae3fea947e5c6b33f1a81aedb1b5850189663b8e8c1a091f66e6d693')

package() {
    sh "$srcdir/test.sh"
    #mkdir -p "$pkgdir/usr/bin"
    #cp "$srcdir/test.sh" "$pkgdir/usr/bin/dummy_test_file"
}

# vim:set ts=8 sts=2 sw=2 et:
