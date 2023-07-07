# Maintainer: Chen Linxuan <me@black-desk.cn>
pkgname=iwyu-mapgen-qt
pkgver=0.20
pkgrel=1
epoch=
pkgdesc=""
arch=('any')
url=""
license=('custom:LLVM')
groups=()
depends=('python')
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=
source=(
	"https://raw.githubusercontent.com/include-what-you-use/include-what-you-use/0.20/LICENSE.TXT"
	"https://raw.githubusercontent.com/include-what-you-use/include-what-you-use/0.20/mapgen/iwyu-mapgen-qt.py"
        "iwyu-mapgen-qt.hook"
        "iwyu-mapgen-qt6.hook"
)
noextract=()
sha256sums=('03ba415fcd109fac41335d797dddfa388b28f6ab893d370a224e579027ace489'
            '39c417aabcf351737bef6e31bbbbcac8a165738f229d8fcfe1e5f3751bc8eb79'
            '6158ef62be23c8bd40ca5f7a2c3eaf7ebee5b45a66ee1d484bfe97ec8c0869ad'
            'ee6ba98b304e94a93413746437e3711badef50a9c916c3e647a1f31c736eed1c')
validpgpkeys=()

package() {
	install -Dm644 LICENSE.TXT "$pkgdir"/usr/share/licenses/"$pkgname"/LICENSE
        install -Dm755 iwyu-mapgen-qt.py "$pkgdir"/usr/bin/iwyu-mapgen-qt
        install -Dm755 iwyu-mapgen-qt.hook "$pkgdir"/usr/share/libalpm/hooks/iwyu-mapgen-qt.hook
        install -Dm755 iwyu-mapgen-qt6.hook "$pkgdir"/usr/share/libalpm/hooks/iwyu-mapgen-qt6.hook
}
