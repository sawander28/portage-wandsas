# Package manager read-only values
# P			package name and version (excluding revision) vim-6.13
# PN		package name vim
# PV		package version (excluding revision) 6.13
# PR		packag revision, or "r0" if no revision exists r1
# PVR		package version and revision 6.13-r1
# PF		full package name vim-6.3-r1
# A			All source files pkg (excluding those not available due to USE-flags)
# CATEGORY	package-category app-editors
# FILESDIR	Path to package files
# WORKDIR	Path to ebuild root directory PORTAGE_BUILDDIR/work
# T			temporary dir may be used by ebuild PORTAGE_BUILDDIR/temp
# D			temporary install PORTAGE_BUILDDIR/image
# HOME		Path to temporary install dir for use by any programs invoked by ebuild
# ROOT		absolute path to root dir into which package is merged
# DISTDIR	contains all files fetched for the package
# EPREFIX	normalized offset-prefix of an offset installation
# ED		${D%/}${EPREFIX}
# EROOT		${D%/}${EPREFIX}
# SYSROOT	absolute path to root dir containing build deps satisfied by DEPEND
# ESYSROOT	${SYSROOT%/}${EPREFIX}/
# MERGE_TYPE type of package being merged: source, binary, buildonly
# REPLACING_VERSIONS whitespace-separated list of all versions replaced as result
# REPLACED_BY_VERSION single version of pkg that is replacing version by ebuild,
#					  if it is uninstalled as part of install

# Ebuild-defined variables
# EAPI          
# DESCRIPTION   short description (80 chars)
# HOMEPAGE      Package's homepage
# SRC_URI       list of source URIs
# SLOT          package's slot
# KEYWORDS      keywords and stabilization
# IUSE          list of all USE flags (excluding arch flags, but with USE_EXPAND)
# REQUIRED_USE  assertions that must be met by configuration
# PROPERTIES    space-delimited list of properties
# RESTRICT      space-delimited list of Portage features to restrict
# DEPEND        package's build deps
# BDEPEND       cbuild deps
# RDEPEND       runtime build deps
# PDEPEND       install deps
# S             temporary build dir, used by src_compile, src_install
#               Default: ${WORKDIR}/${P}
