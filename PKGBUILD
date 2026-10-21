
# Maintainer: Masahiro Sugaya [xsigil@section-9.sh](https://www.google.com/search?q=mailto%3Axsigil%40section-9.sh)

pkgname=hqss-impl
pkgver=4.1.0
pkgrel=1
pkgdesc="MONOLITH Protocol HQSS-v4 Universal Provisioning and Reconstruction Tools"
arch=('any')
url="https://monolith-id.com"
license=('MIT')
depends=('openssl' 'libgfshare' 'xxd' 'coreutils')
source=("$pkgname-$pkgver.tar.gz::https://github.com/xsigil/hqss-impl/archive/refs/tags/v$pkgver.tar.gz")
sha256sums=('cce10d024b3d394b4044794ea6b3dcaaad2d0fcfe054df6c0f43143d89584da6')

package() {
cd "$pkgname-$pkgver"

```
install -Dm755 gen.sh "$pkgdir/usr/bin/hqss-gen"
install -Dm755 restore.sh "$pkgdir/usr/bin/hqss-restore"

install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"

```

}
