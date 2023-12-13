pkgname=adilhyz-themes
pkgver=1.0
pkgrel=2
pkgdesc="Themes For Needs"
arch=('any')
url="https://github.com/adilhyz/adilhyz-themes"
license=('GPL3')

prepare() {

	cp -af ../themes/. ${srcdir}

}

package() {

	local themes_dir=${pkgdir}/usr/share/themes
	mkdir -p ${themes_dir}
	cp -r ${srcdir}/* ${themes_dir}

}
