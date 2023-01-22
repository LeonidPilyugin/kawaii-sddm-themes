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
sha256sums=('ce9551ed7f8bcc7ae1491e1114ecabcf8c390c5b27c13080d979eb33fa6bb8ac')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/sddm/themes
    install -dm755 $dir
    cp -r $srcdir/* $dir/
}

