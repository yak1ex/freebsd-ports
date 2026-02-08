PORTNAME= influxdb3
DISTVERSIONPREFIX= v
DISTVERSION= 3.4.0
CATEGORIES= databases

MAINTAINER= yak1ex@gmail.com
COMMENT= Scalable datastore for metrics, events, and real-time analytics
WWW= https://github.com/influxdata/influxdb

USES= cargo
USE_GITHUB= yes
GH_ACCOUNT= influxdata
GH_PROJECT= influxdb
CARGO_USE_GITHUB= yes

BUILD_DEPENDS= protoc:devel/protobuf

GIT_HASH= 9e26dadce59a3e453b80e8d2a9342da5bde3210a
GIT_HASH_SHORT= 9e26dad
MAKE_ENV= GIT_HASH=${GIT_HASH} GIT_HASH_SHORT=${GIT_HASH_SHORT}
CARGO_INSTALL_PATH = influxdb3

.include <bsd.port.mk>
