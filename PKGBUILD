pkgname=2gis-stavropol
pkgver=12
pkgrel=1
pkgdesc="Map of Stavropol for 2GIS, December 2012"
arch=('i686' 'x86_64')
url="http://stavropol.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.12.0.2')
source=("http://download.2gis.ru/arhives/2GISData_Stavropol-12.orig.zip")
md5sums=('cfdd09b13cf2418bcd705f40670ca77d')

build() {
  cd $startdir
# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Stavropol.dgdat "${startdir}/pkg/opt/2gis/stavropol.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Stavropol.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Stavropol.dglf" || return 1
}
