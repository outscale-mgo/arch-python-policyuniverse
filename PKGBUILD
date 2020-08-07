# Maintainer: Matthias gatto <matthias.gatto@outscale.com>
# Reference: PKGBUILD(5)

pkgname=python-policyuniverse
pkgver=1.3.2
pkgrel=1
pkgdesc='This package provides classes to parse AWS IAM and Resource Policies.'

arch=('any')
url='https://github.com/Netflix-Skunkworks/policyuniverse'
license=(BSD)

makedepends=('python-pip')

package() {
	PIP_CONFIG_FILE=/dev/null pip install --isolated --root="$pkgdir" --ignore-installed --no-deps policyuniverse==1.3.2
}
