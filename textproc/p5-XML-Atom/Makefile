# $NetBSD: Makefile,v 1.29 2017/06/12 07:45:46 maya Exp $

DISTNAME=	XML-Atom-0.41
PKGNAME=	p5-${DISTNAME}
PKGREVISION=	7
CATEGORIES=	textproc perl5
MASTER_SITES=	${MASTER_SITE_PERL_CPAN:=XML/}

MAINTAINER=	kleink@NetBSD.org
HOMEPAGE=	http://search.cpan.org/dist/XML-Atom/
COMMENT=	Atom feed and API implementation
LICENSE=	${PERL5_LICENSE}

DEPENDS+=	p5-Class-Data-Inheritable-[0-9]*:../../devel/p5-Class-Data-Inheritable
DEPENDS+=	p5-XML-LibXML>=1.64:../../textproc/p5-XML-LibXML
#DEPENDS+=	{perl>=5.7.3,p5-MIME-Base64-[0-9]*}:../../converters/p5-MIME-Base64
DEPENDS+=	p5-XML-XPath-[0-9]*:../../textproc/p5-XML-XPath

# Client/Server for Atom API
DEPENDS+=	p5-libwww-[0-9]*:../../www/p5-libwww
DEPENDS+=	p5-LWP-Authen-Wsse-[0-9]*:../../www/p5-LWP-Authen-Wsse
DEPENDS+=	p5-Digest-SHA1-[0-9]*:../../security/p5-Digest-SHA1
DEPENDS+=	p5-DateTime-[0-9]*:../../time/p5-DateTime

# Feed and API Auto-discovery
DEPENDS+=	p5-HTML-Parser-[0-9]*:../../www/p5-HTML-Parser

MAKE_ENV+=		PERL_USE_UNSAFE_INC=1
PERL5_PACKLIST=		auto/XML/Atom/.packlist

.include "../../lang/perl5/module.mk"
.include "../../mk/bsd.pkg.mk"
