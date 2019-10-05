# Maintainer: Ryan Eschinger <ryanesc[at]gmail[dot]com>

pkgname=argocd-bin
pkgver=1.2.1
pkgrel=1
pkgdesc="Declarative continuous deployment for Kubernetes."
arch=('x86_64')
url="https://github.com/argoproj/argo-cd"
license=('Apache')
source=("argocd_$pkgver::https://github.com/argoproj/argo-cd/releases/download/v$pkgver/argocd-linux-amd64")
sha256sums=('7ad6642acc2ff83bf7411e22c296dafa1358ad49a3ce520b9f72a79a5a734043')

package() {
  install -Dm755 "argocd_$pkgver" "$pkgdir/usr/bin/argocd"
}
