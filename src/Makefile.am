lib_LIBRARIES = \
	libbtdht.a

libbtdht_a_SOURCES = \
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

libbtdht_a_LIBADD = \
	../btutils/src/libbtutils.a

libbtdht_a_CXXFLAGS = \
	-std=c++11 \
	-I../btutils/src
