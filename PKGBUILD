pkgname=nvu-extension-epiphany
pkgver=1.0
pkgrel=1
pkgdesc="Gnome's Epiphany Browser extension for Nvu"
url="http://www.nvu.com/Building_From_Source.php#tipsandhints"
license=""
depends=()
makedepends=()
conflicts=('nvu-extension-konqueror' 'nvu-extension-firefox' \
           'nvu-extension-seamonkey' 'nvu-extension-opera' \
           'nvu-extension-mozilla')
replaces=()
backup=()
provides=()
install=
source=(mozilla-ext)
md5sums=('c53597a55921c871505a645dc124bb80')

build() {
  mkdir -p $startdir/pkg/opt/mozilla/bin
  install -m755  $startdir/src/mozilla-ext $startdir/pkg/opt/mozilla/bin/
}
