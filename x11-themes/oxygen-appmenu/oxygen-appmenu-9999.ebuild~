# Copyright 1999-2011 Gentoo Foundation
# Distributed under the terms of the GNU General Public License v2
# $Header: $

EAPI=4

KDE_SCM="git"

inherit cmake-utils git-2

DESCRIPTION="Oxygen-appmenu is an oxygen style for kwin displaying application menu in titlebar (via menu button)"
HOMEPAGE="http://kde-look.org/content/show.php?content=141254"
EGIT_REPO_URI="git://anongit.kde.org/scratch/cedric/"

LICENSE="GPL-2 LGPL-2"
KEYWORDS=""
SLOT="0"
IUSE=""

RDEPEND="
    x11-misc/appmenu-qt
"
DEPEND="${RDEPEND}"

src_install() {
  cmake-utils_src_install
}