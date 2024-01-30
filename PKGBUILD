# Maintainer: pitman2e
pkgname=disable-acpi-wake
pkgver=1.0.1
pkgrel=1
pkgdesc="Disable ACPI Wake"
arch=('any')
conflicts=()
provides=()
source=("disable-acpi-wake.service")
sha512sums=("SKIP")

package() {
  install -Dm744 "${srcdir}/disable-acpi-wake.service" "${pkgdir}/usr/lib/systemd/system/disable-acpi-wake.service"
}
