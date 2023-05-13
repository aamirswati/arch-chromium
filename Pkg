pkgname="rpm-package-name"
pkgver="0.0.1"
pkgrel="1"
pkgdesc="Mini description of the RPM package."
arch=("x86_64")

source=("filename.rpm")

sha256sums=("SKIP")

package() {
  find $srcdir/ -mindepth 1 -maxdepth 1 -type d | xargs cp -r -t "$pkgdir"
}
