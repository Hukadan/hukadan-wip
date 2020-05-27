COMMENT =		A Python 3 asyncio Matrix framework

MODPY_EGG_VERSION =	0.7.2

DISTNAME =		mautrix-telegram-${MODPY_EGG_VERSION}
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

#absent alembic telethon
RUN_DEPENDS =		net/py-mautrix \
			net/py-telethon \
			textproc/py-commonmark${MODPY_FLAVOR} \
			www/py-aiohttp \
			textproc/py-ruamel.yaml${MODPY_FLAVOR} \
			devel/py-magic${MODPY_FLAVOR} \
			databases/py-telethon-session-sqlalchemy \
			databases/py-sqlalchemy${MODPY_FLAVOR}

# No tests in the upstream library
NO_TEST =		Yes
#
.include <bsd.port.mk>
