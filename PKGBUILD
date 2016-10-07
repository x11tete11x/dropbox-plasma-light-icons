pkgname=dropbox-plasma-light-icons-git
_pkgname=dropbox-plasma-light-icons
pkgver=1
pkgrel=1
pkgdesc="Dropbox icons for Plasma 5 Light Panels"
arch=('any')
url="http://i.imgur.com/ZQNQM.png"
license=('GPL')
depends=('hicolor-icon-theme' 'dropbox')
conflicts=('dropbox-kfilebox-icons'
           'dropbox-plasma-dark-icons')           
source=(https://github.com/x11tete11x/dropbox-plasma-light-icons.git)
md5sums=(SKIP)
install="dropbox-plasma-light-icons.install"

package(){
  install -d "${pkgdir}/usr/share/icons/hicolor/"
  cp -r ${srcdir}/${_pkgname}/icons/* "${pkgdir}/usr/share/icons/hicolor/"
}
