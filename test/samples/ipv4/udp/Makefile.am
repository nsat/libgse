################################################################################
#	Name       : Makefile
#	Author     : Didier Barvaux <didier.barvaux@toulouse.viveris.com>
#	Description: create the GSE test program
################################################################################

SUBDIRS = . \
	rtp

TESTS = \
	$(top_builddir)/test/non_regression_tests.sh \
	$(top_builddir)/test/non_regression_tests_no_alloc.sh

TESTS_ENVIRONMENT = builddir=$(top_builddir)

EXTRA_DIST = \
	source.pcap \
	fragmented.pcap \
	refragmented.pcap\
	fragmented_label_0.pcap \
	fragmented_label_3.pcap \
	refragmented_label_0.pcap \
	refragmented_label_3.pcap
