# $NetBSD: Makefile,v 1.7 2016/06/08 17:43:48 wiz Exp $

DISTNAME=	WTForms-Alchemy-0.13.0
PKGNAME=	${PYPKGPREFIX}-${DISTNAME:tl}
CATEGORIES=	databases python www
MASTER_SITES=	${MASTER_SITE_PYPI:=W/WTForms-Alchemy/}

MAINTAINER=	rodent@NetBSD.org
HOMEPAGE=	https://github.com/kvesteri/wtforms-alchemy
COMMENT=	Generates WTForms forms from SQLAlchemy models
LICENSE=	modified-bsd

DEPENDS+=	${PYPKGPREFIX}-sqlalchemy>=0.8.0:../../databases/py-sqlalchemy
DEPENDS+=	${PYPKGPREFIX}-wtforms>=1.0.4:../../www/py-wtforms
DEPENDS+=	${PYPKGPREFIX}-wtforms-components>=0.9.2:../../www/py-wtforms-components
DEPENDS+=	${PYPKGPREFIX}-sqlalchemy-utils>=0.23.1:../../databases/py-sqlalchemy-utils
DEPENDS+=	${PYPKGPREFIX}-six>=1.4.1:../../lang/py-six

USE_LANGUAGES=	# none

.include "../../lang/python/egg.mk"
.include "../../mk/bsd.pkg.mk"
