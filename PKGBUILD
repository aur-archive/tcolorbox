# Contributor: box0

pkgname=tcolorbox
pkgver=2.21
pkgrel=2
pkgdesc="up-to-date version of the tcolorbox package"
arch=("any")
license=('LPPL')
url="http://www.ctan.org/tex-archive/macros/latex/contrib/tcolorbox"
depends=('texlive-core')
source=("http://mirrors.ctan.org/macros/latex/contrib/tcolorbox.zip")
md5sums=('c5cb045e3c7394293695ccc96a407219')
#md5sums=('3f98a46bb59494cddc7f5b3815b7b198')

install="tcolorbox.install"

package()
{
        mkdir -p $pkgdir/usr/share/texmf/tex/latex/${pkgname}
        cp $srcdir/${pkgname}/* $pkgdir/usr/share/texmf/tex/latex/${pkgname}
}