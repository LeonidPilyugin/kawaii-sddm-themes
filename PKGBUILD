# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-sddm-themes
pkgver=2.1
pkgrel=1
pkgdesc='Kawaii sddm themes.'
groups=(kawaii)
url='https://github.com/LeonidPilyugin/kawaii-sddm-themes'
depends=(sddm)
arch=(x86_64)
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('138e85381ef3b442e733c40a2f21810ab546b630d658dd89425d30161e4d2ca7')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/sddm/themes
    install -dm755 $dir
    cp -r $srcdir/* $dir/
}

