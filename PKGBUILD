# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    PKGBUILD                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: Lanhild <archlan@protonmail.com>           +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2022/01/08 19:41:27 by Lanhild           #+#    #+#              #
#    Updated: 2022/01/15 12:40:52 by Lanhild          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #

pkgname=archlan-grub-theme
pkgver=1.0
pkgrel=1
pkgdesc="ArchLan base grub theme"
url="https://github.com/archlan/archlan-grub-theme"
arch=('any')
license=('GPL3')
makedepends=()
depends=(grub)
conflicts=()
provides=("${pkgname}")
options=(!strip)

prepare() {
	cp -af ../files/. ${srcdir}
}

package() {
    sudo ${srcdir}/install.sh
}