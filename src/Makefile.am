lib_LTLIBRARIES = \
	libbtdht.la

libbtdht_la_SOURCES = \
	blockallocator.h \
	blockallocator.cpp \
	Buffer.h \
	crc32c.cpp \
	dht.h \
	dht.cpp \
	DhtImpl.h \
	DhtImpl.cpp \
	DHTMessage.h \
	DHTMessage.cpp \
	ExternalIPCounter.h \
	ExternalIPCounter.cpp

libbtdht_la_LIBADD = \
	../btutils/src/libbtutils.la

libbtdht_la_CXXFLAGS = \
	-std=c++11 \
	-I../btutils/src
