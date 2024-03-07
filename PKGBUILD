# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-sddm-themes
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii sddm themes.'
groups=(kawaii)
url='https://github.com/LeonidPilyugin/kawaii-sddm-themes'
depends=(sddm)
arch=(x86_64)
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('b22008760c03a2d393e24378f57853c4297a3ce3799fd6d13f2a2c8c537b757c')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/sddm/themes
    install -dm755 $dir
    cp -r $srcdir/* $dir/
}

