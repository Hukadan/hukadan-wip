COMMENT =		SQLAlchemy backend for Telethon session storage

MODPY_EGG_VERSION =	0.2.15

DISTNAME =		telethon-session-sqlalchemy-${MODPY_EGG_VERSION}
PKGNAME =		py-${DISTNAME}

CATEGORIES =		databases

HOMEPAGE =		https://github.com/tulir/telethon-session-sqlalchemy

MAINTAINER =		Hukadan <me@hukadan.org>

# MIT
PERMIT_PACKAGE =	Yes

MODULES =		lang/python

MODPY_PI =		Yes
MODPY_SETUPTOOLS =	Yes
MODPY_VERSION =		${MODPY_DEFAULT_VERSION_3}

RUN_DEPENDS =		databases/py-sqlalchemy${MODPY_FLAVOR}

# No tests in the upstream library
NO_TEST =		Yes
#
.include <bsd.port.mk>
