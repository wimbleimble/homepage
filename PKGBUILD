# Maintainer: Kate Thomas <wimbleimble@protonmail.com>
pkgname=wimbleimble-homepage
pkgver=0.0.2
pkgrel=1
pkgdesc="Web server hosting a homepage for your web browser"
url="https://www.wimbleimble.xyz"
arch=("x86_64")
license=('GPL')
depends=("python")
source=("index.html" "wimbleimble-homepage.service")
sha512sums=("SKIP" "SKIP")

package() {
    install -D -m644 "${srcdir}/wimbleimble-homepage.service" "${pkgdir}/usr/lib/systemd/user/wimbleimble-homepage.service"
    install -D -m644 "${srcdir}/index.html" "${pkgdir}/usr/share/${pkgname}/index.html"
}
