# Maintainer: Buce <dmbuce@gmail.com>
# Automatically generated by pip2arch on 2011-01-16

pkgname=python-nbt
pkgver=1.4.1
pkgrel=1
pkgdesc="Named Binary Tag Reader/Writer"
url="http://github.com/twoolie/NBT"
depends=('python')
makedepends=('python-distribute')
license=('MIT')
arch=('any')
source=("$pkgname::git+https://github.com/twoolie/NBT.git#tag=version-$pkgver")
md5sums=('SKIP')

package() {
    cd "$srcdir/$pkgname"
    python setup.py install --root="$pkgdir" --optimize=1
    install -D -m644 LICENSE.txt "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}

# vim: set ts=4 sw=4 et:
