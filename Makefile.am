
SUBDIRS = src sample
DIST_SUBDIRS = src sample

ACLOCAL_AMFLAGS = -I m4

CHANGE_LOG_GEN_BIN = scripts/cvs2cl.pl
CHANGE_LOG_GEN_FLAGS = -t -r -b --accum -I ChangeLog --gmt --prune

ChangeLog::
	$(CHANGE_LOG_GEN_BIN) $(CHANGE_LOG_GEN_FLAGS)
