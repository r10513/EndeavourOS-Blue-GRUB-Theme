# Base Maintainer: Filipe Laíns (FFY00) <lains@archlinux.org>
# Original Source: https://github.com/Se7endAY/grub2-theme-vimix
# Maintainer: EndeavourOS-Team <info@endeavouros.com>
pkgname=grub2-theme-endeavouros
pkgver=20220602
pkgrel=1
pkgdesc='EndeavourOS grub2 theme'
arch=(any)
url='https://github.com/endeavouros-team/'
license=('GPL3')
depends=('grub')
makedepends=('git')
replaces=('vimix-grub' 'grub-theme-vimix' 'grub-themes-vimix')
makedepends=('git')
source=("https://github.com/EndeavourOS-archive/grub2-theme-endeavouros/archive/refs/tags/${pkgver}.tar.gz")
sha512sums=('09c82dde9f49a3eb1ded040e011fbb4f682b47e5bbc3399fe4944b0d4935c40021b293e92158e90026bca2286aa5eb6d9b858ddb13b80911b9b1d796b22089c8')

package() {
    install -dm 755 "$pkgdir/boot/grub/themes/EndeavourOS"
    cp -r --no-preserve=ownership "grub2-theme-endeavouros-$pkgver/EndeavourOS" "$pkgdir/boot/grub/themes/"
}
