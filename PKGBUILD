# Maintainer: Michael Nussbaum <michaelnussbaum08@gmail.com>

pkgname=firefox-gopassbridge
pkgver=0.1.1
pkgrel=1
pkgdesc='Gopass Bridge Firefox extension allows searching and inserting login credentials from the gopass password manager'
url=https://github.com/martinhoefling/gopassbridge
arch=('any')
license=('MIT')
source=("https://addons.cdn.mozilla.net/user-media/addons/852556/gopass_bridge-0.1.1-fx-linux.xpi")
noextract=("${source##*/}")
sha256sums=('9aec7235b52609b983a8e9d116a5a0be93bf618e6ba18d9d51ad7db72fecd9f9')

package() {
    install -Dm644 "${source##*/}" "$pkgdir"/usr/lib/firefox/browser/extensions/gopass_bridge-0.1.1-fx-linux.xpi
}

# vim:set ts=2 sw=2 et:
