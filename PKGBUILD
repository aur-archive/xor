# Maintainer: Jay MJ <jskier[at]gmail[dot]com>
pkgname=xor
pkgver=0.2
pkgrel=2
pkgdesc="Simple xor cli application written in c by Luigi Auriemma"
url="http://aluigi.org"
arch=('x86_64' 'i686')
license=('None')
makedepends=('gcc')
install=''
source=("http://aluigi.altervista.org/mytoolz/${pkgname}.zip")
md5sums=('62025a6917dcd23e3e3dda137404540e')

build() {
  cd "${srcdir}"
  gcc xor.c -o xor
  rm *.*
}
package() {
	mkdir -p ${pkgdir}/usr/bin
	mv xor ${pkgdir}/usr/bin/
}

