COMMENT =		A Python 3 asyncio Matrix framework

MODPY_EGG_VERSION =	1.13.0

DISTNAME =		Telethon-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME}

CATEGORIES =		net

HOMEPAGE =		https://github.com/tulir/mautrix-python

MAINTAINER =		Hukadan <me@hukadan.org>

# BSD
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI =		Yes
MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}
MODPY_SETUPTOOLS =	Yes

RUN_DEPENDS =		security/py-aes${MODPY_FLAVOR} \
			security/py-rsa${MODPY_FLAVOR}

# No tests in the upstream library
NO_TEST =		Yes
#
.include <bsd.port.mk>
