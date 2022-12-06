# Maintainer: pitman2e
pkgname=disable_acpi_wake
pkgver=1.0.0
pkgrel=2
pkgdesc="Disable ACPI Wake"
arch=('any')
conflicts=()
provides=()
source=("disable_acpi_wake.service")
sha512sums=("SKIP")

package() {
  install -Dm744 "${srcdir}/disable_acpi_wake.service" "${pkgdir}/usr/lib/systemd/system/disable_acpi_wake.service"
}
