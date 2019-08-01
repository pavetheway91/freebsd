# $FreeBSD$

.PATH: ${SRCTOP}/sys/dev/md

KMOD=	geom_md
SRCS=	md.c opt_md.h opt_geom.h opt_rootdevname.h vnode_if.h

CFLAGS+= -I${SRCTOP}/sys/contrib/zstd/lib/freebsd

.include <bsd.kmod.mk>
