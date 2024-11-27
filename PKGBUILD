# Maintainer: Jonathan Schilling <jonathan.schilling@mail.de>
pkgname=vtk-versioned-links
pkgver=9.1.0
pkgrel=26
pkgdesc="Version-specific soft links for VTK"
arch=(any)
url="https://vtk.org/"
license=('GPL')
depends=('vtk=9.1.0-26')
provides=(vtk-versioned-links)
conflicts=(vtk-versioned-links)

package() {
	mkdir -p ${pkgdir}/usr/include

	# include headers
	ln -sf /usr/include/vtk "${pkgdir}/usr/include/vtk-9.1"
}

