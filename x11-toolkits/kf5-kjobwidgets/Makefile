# Created by: tcberner
# $FreeBSD$

PORTNAME=	kjobwidgets
PORTVERSION=	${KDE_FRAMEWORKS_VERSION}
CATEGORIES=	x11-toolkits kde kde-frameworks

MAINTAINER=	kde@FreeBSD.org
COMMENT=	KF5 widgets for tracking KJob instance

USES=		cmake:outsource compiler:c++11-lib kde:5 tar:xz
USE_KDE=	coreaddons ecm widgetsaddons
USE_QT5=	buildtools_build core dbus gui linguisttools \
		qmake_build widgets x11extras

.include <bsd.port.mk>
