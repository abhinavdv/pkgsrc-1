# $NetBSD: Makefile,v 1.9 2017/06/21 14:15:00 taca Exp $

DISTNAME=	childprocess-0.7.0
PKGNAME=	${RUBY_PKGPREFIX}-${DISTNAME}
CATEGORIES=	ruby sysutils

MAINTAINER=	rodent@NetBSD.org
HOMEPAGE=	https://github.com/jarib/childprocess
COMMENT=	Simple and reliable solution for controlling external programs
LICENSE=	mit

DEPENDS+=	${RUBY_PKGPREFIX}-ffi>=1.0.11:../../devel/ruby-ffi

USE_LANGUAGES=	# none

.include "../../lang/ruby/gem.mk"
.include "../../mk/bsd.pkg.mk"
