NULL=

bin_PROGRAMS=irixltclient

irixltclient_SOURCES=				\
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
