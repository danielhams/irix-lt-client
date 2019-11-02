NULL=

bin_PROGRAMS=irixltclient

noinst_HEADERS=					\
	print.hpp				\
	session_view.hpp			\
	torrent_view.hpp			\
	$(NULL)

irixltclient_SOURCES=				\
	print.cpp				\
	session_view.cpp			\
	torrent_view.cpp			\
	irixltclient.cpp			\
	$(NULL)

AM_CFLAGS=					\
	$(IRIXLTCLIENT_DEPS_CFLAGS)		\
	$(NULL)

irixltclient_LDFLAGS=				\
	-pthread				\
	$(NULL)

irixltclient_LDADD=				\
	$(LTLIBICONV)				\
	$(IRIXLTCLIENT_DEPS_LIBS)		\
	-lpthread				\
	$(NULL)

CLEANFILES=					\
	.libs					\
	$(NULL)
