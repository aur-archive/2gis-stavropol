pkgname=2gis-stavropol
pkgver=35
pkgrel=1
pkgdesc="Map of Stavropol for 2GIS, November 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/stavropol/products/download#linux"
license=('custom')
depends=('2gis>=3.14.9.0')
source=("http://download.2gis.com/arhives/2GISData_Stavropol-35.orig.zip")
md5sums=('888aa5272c88799e0a99866bb53837b2')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Stavropol.dgdat" "${pkgdir}/opt/2gis/2gis-stavropol.dgdat" || return 1
  
}
