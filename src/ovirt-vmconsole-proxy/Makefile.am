include $(top_srcdir)/build/subst.inc

MAINTAINERCLEANFILES = \
	$(srcdir)/Makefile.in \
	$(NULL)
CLEANFILES = \
	NOTICE \
	ovirt-vmconsole-proxy.conf \
	ssh_config \
	$(NULL)

EXTRA_DIST = \
	NOTICE.in \
	$(NULL)

SUFFIXES = .in

SUBDIRS = \
	ovirt-vmconsole-proxy-sshd \
	$(NULL)

nodist_libexec_SCRIPTS = \
	ovirt-vmconsole-proxy-keys \
	ovirt-vmconsole-proxy-shell \
	$(NULL)

nodist_pkgproxydata_DATA = \
	ovirt-vmconsole-proxy.conf \
	ssh_config \
	$(NULL)

confdir = $(pkgproxysysconfdir)/conf.d

nodist_conf_DATA = \
	NOTICE \
	$(NULL)
