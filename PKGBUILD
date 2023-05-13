pkgname="chromium"
pkgver="112.0.5615.165-1.2"
pkgrel="1"
pkgdesc="Google's open source browser project."
arch=("x86_64")

source=("chromium-112.0.5615.165-1.2.aarch64.rpm")

sha256sums=("SKIP")

package() {
  find $srcdir/ -mindepth 1 -maxdepth 1 -type d | xargs cp -r -t "$pkgdir"
}
