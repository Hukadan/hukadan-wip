COMMENT =		A Python 3 asyncio Matrix framework

MODPY_EGG_VERSION =	0.4.2

DISTNAME =		mautrix-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME}

CATEGORIES =		net

HOMEPAGE =		https://github.com/tulir/mautrix-python

MAINTAINER =		Hukadan <me@hukadan.org>

# MPL2
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI =		Yes
MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}
MODPY_SETUPTOOLS =	Yes

RUN_DEPENDS =		devel/py-attrs${MODPY_FLAVOR} \
			devel/py-magic${MODPY_FLAVOR} \
			www/py-aiohttp
# No tests in the upstream library
NO_TEST =		Yes
#
.include <bsd.port.mk>
