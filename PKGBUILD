# Maintainer: Rafael from RebornOS

pkgname=ttf-righteous-regular
_pkgname=Righteous-Regular
pkgver=1.0
pkgrel=2
pkgdesc='Righteous Regular font'
arch=('any')
url='https://fonts.google.com/specimen/Righteous'
license=('SIL Open Font License')
source=('OFL.txt'
        "${_pkgname}.ttf")
sha256sums=('1c5bc055869d5e9151ec7774082727db720ec4293c65be67f91a4bdcaeb02998'
            '4c3cdc5de2d70c4ee75fc9c1723a6b8f2d7316f49b383335fd8257a17dd88ade')

package() {
    install -d ${pkgdir}/usr/share/fonts/TTF/
    install -m644 ${_pkgname}.ttf ${pkgdir}/usr/share/fonts/TTF/
    install -D -m644 OFL.txt ${pkgdir}/usr/share/licenses/${pkgname}/OFL.txt
}
