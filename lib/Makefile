# Makefile.in generated by automake 1.14.1 from Makefile.am.
# lib/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2013 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



# Have to add top_builddir/include to pick up made qdp_config_internal.h


am__is_gnu_make = test -n '$(MAKEFILE_LIST)' && test -n '$(MAKELEVEL)'
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/qdp--
pkgincludedir = $(includedir)/qdp--
pkglibdir = $(libdir)/qdp--
pkglibexecdir = $(libexecdir)/qdp--
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
am__append_1 = -I../other_libs/xpath_reader/include
#am__append_2 = -I../other_libs//include -I../other_libs//include
am__append_3 = qdp_xmlio.cc qdp_iogauge.cc qdp_qdpio.cc qdp_qio_strings.cc qdp_map_obj_disk.cc
#am__append_4 = qdp_hdf5.cc

# Scalar	
am__append_5 = qdp_scalar_init.cc qdp_scalar_layout.cc \
	qdp_scalar_specific.cc qdp_scalarsite_specific.cc


# Parallel-scalar
#am__append_6 = qdp_parscalar_init.cc qdp_parscalar_layout.cc \
#	qdp_parscalar_specific.cc \
#	qdp_scalarsite_specific.cc


# Optimized code using sse extensions
#am__append_7 = \
#	scalarsite_sse/qdp_scalarsite_sse.cc \
#	scalarsite_sse/qdp_scalarsite_linalg_double.cc \
#	scalarsite_sse/sse_blas_local_sumsq_double.cc \
#	scalarsite_sse/sse_blas_local_vcdot_double.cc \
#	scalarsite_sse/sse_blas_local_vcdot_real_double.cc \
#	scalarsite_sse/sse_blas_vaxmbyz4_double.cc \
#	scalarsite_sse/sse_blas_vaxmyz4_double.cc \
#	scalarsite_sse/sse_blas_vaxpbyz4_double.cc \
#	scalarsite_sse/sse_blas_vaxpy4_double.cc \
#	scalarsite_sse/sse_blas_vaypx4_double.cc \
#	scalarsite_sse/sse_blas_vscal4_double.cc \
#	scalarsite_sse/sse_linalg_m_eq_scal_m_double.cc \
#	scalarsite_sse/sse_linalg_m_peq_m_double.cc \
#	scalarsite_sse/sse_linalg_m_eq_mm_double.cc \
#	scalarsite_sse/sse_linalg_m_eq_mh_double.cc \
#	scalarsite_sse/sse_linalg_m_eq_hm_double.cc \
#	scalarsite_sse/sse_linalg_m_eq_hh_double.cc


# Scalar with Vector extensions
#am__append_8 = qdp_scalarvec_init.cc qdp_scalarvec_layout.cc \
#	qdp_scalarvec_specific.cc qdp_scalarvecsite_specific.cc


# Parallel scalar with Vector extensions
#am__append_9 = qdp_parscalarvec_init.cc qdp_parscalarvec_layout.cc \
#	qdp_parscalarvec_specific.cc qdp_scalarvecsite_specific.cc


# Optimized code using sse extensions
#am__append_10 = qdp_scalarvecsite_sse.cc
am__append_11 = qdp_default_allocator.cc
#am__append_12 = qdp_bgq_threadbind.cc
am__append_13 = qdp_generic_threadbind.cc
subdir = lib
DIST_COMMON = $(srcdir)/Makefile.in $(srcdir)/Makefile.am \
	$(top_srcdir)/config/mkinstalldirs \
	$(top_srcdir)/config/depcomp
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/acinclude.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) $(top_srcdir)/config/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/include/qdp_config_internal.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__installdirs = "$(DESTDIR)$(libdir)"
LIBRARIES = $(lib_LIBRARIES)
ARFLAGS = cru
AM_V_AR = $(am__v_AR_$(V))
am__v_AR_ = $(am__v_AR_$(AM_DEFAULT_VERBOSITY))
am__v_AR_0 = @echo "  AR      " $@;
am__v_AR_1 = 
libqdp_a_AR = $(AR) $(ARFLAGS)
libqdp_a_LIBADD =
am__libqdp_a_SOURCES_DIST = qdp_map.cc qdp_subset.cc qdp_random.cc \
	qdp_layout.cc qdp_io.cc qdp_byteorder.cc qdp_util.cc \
	qdp_stdio.cc qdp_profile.cc qdp_strnlen.cc qdp_crc32.cc \
	qdp_stopwatch.cc qdp_rannyu.cc qdp_xmlio.cc qdp_iogauge.cc \
	qdp_qdpio.cc qdp_qio_strings.cc qdp_map_obj_disk.cc \
	qdp_hdf5.cc qdp_scalar_init.cc qdp_scalar_layout.cc \
	qdp_scalar_specific.cc qdp_scalarsite_specific.cc \
	qdp_parscalar_init.cc qdp_parscalar_layout.cc \
	qdp_parscalar_specific.cc scalarsite_sse/qdp_scalarsite_sse.cc \
	scalarsite_sse/qdp_scalarsite_linalg_double.cc \
	scalarsite_sse/sse_blas_local_sumsq_double.cc \
	scalarsite_sse/sse_blas_local_vcdot_double.cc \
	scalarsite_sse/sse_blas_local_vcdot_real_double.cc \
	scalarsite_sse/sse_blas_vaxmbyz4_double.cc \
	scalarsite_sse/sse_blas_vaxmyz4_double.cc \
	scalarsite_sse/sse_blas_vaxpbyz4_double.cc \
	scalarsite_sse/sse_blas_vaxpy4_double.cc \
	scalarsite_sse/sse_blas_vaypx4_double.cc \
	scalarsite_sse/sse_blas_vscal4_double.cc \
	scalarsite_sse/sse_linalg_m_eq_scal_m_double.cc \
	scalarsite_sse/sse_linalg_m_peq_m_double.cc \
	scalarsite_sse/sse_linalg_m_eq_mm_double.cc \
	scalarsite_sse/sse_linalg_m_eq_mh_double.cc \
	scalarsite_sse/sse_linalg_m_eq_hm_double.cc \
	scalarsite_sse/sse_linalg_m_eq_hh_double.cc \
	qdp_scalarvec_init.cc qdp_scalarvec_layout.cc \
	qdp_scalarvec_specific.cc qdp_scalarvecsite_specific.cc \
	qdp_parscalarvec_init.cc qdp_parscalarvec_layout.cc \
	qdp_parscalarvec_specific.cc qdp_scalarvecsite_sse.cc \
	qdp_default_allocator.cc qdp_bgq_threadbind.cc \
	qdp_generic_threadbind.cc
am__objects_1 = qdp_xmlio.$(OBJEXT) \
	qdp_iogauge.$(OBJEXT) \
	qdp_qdpio.$(OBJEXT) \
	qdp_qio_strings.$(OBJEXT) \
	qdp_map_obj_disk.$(OBJEXT)
#am__objects_2 = qdp_hdf5.$(OBJEXT)
am__objects_3 = qdp_scalar_init.$(OBJEXT) \
	qdp_scalar_layout.$(OBJEXT) \
	qdp_scalar_specific.$(OBJEXT) \
	qdp_scalarsite_specific.$(OBJEXT)
#am__objects_4 = qdp_parscalar_init.$(OBJEXT) \
#	qdp_parscalar_layout.$(OBJEXT) \
#	qdp_parscalar_specific.$(OBJEXT) \
#	qdp_scalarsite_specific.$(OBJEXT)
am__dirstamp = $(am__leading_dot)dirstamp
#am__objects_5 = scalarsite_sse/qdp_scalarsite_sse.$(OBJEXT) \
#	scalarsite_sse/qdp_scalarsite_linalg_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_local_sumsq_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_local_vcdot_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_local_vcdot_real_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vaxmbyz4_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vaxmyz4_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vaxpbyz4_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vaxpy4_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vaypx4_double.$(OBJEXT) \
#	scalarsite_sse/sse_blas_vscal4_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_eq_scal_m_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_peq_m_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_eq_mm_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_eq_mh_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_eq_hm_double.$(OBJEXT) \
#	scalarsite_sse/sse_linalg_m_eq_hh_double.$(OBJEXT)
#am__objects_6 = qdp_scalarvec_init.$(OBJEXT) \
#	qdp_scalarvec_layout.$(OBJEXT) \
#	qdp_scalarvec_specific.$(OBJEXT) \
#	qdp_scalarvecsite_specific.$(OBJEXT)
#am__objects_7 =  \
#	qdp_parscalarvec_init.$(OBJEXT) \
#	qdp_parscalarvec_layout.$(OBJEXT) \
#	qdp_parscalarvec_specific.$(OBJEXT) \
#	qdp_scalarvecsite_specific.$(OBJEXT)
#am__objects_8 =  \
#	qdp_scalarvecsite_sse.$(OBJEXT)
am__objects_9 =  \
	qdp_default_allocator.$(OBJEXT)
#am__objects_10 =  \
#	qdp_bgq_threadbind.$(OBJEXT)
am__objects_11 =  \
	qdp_generic_threadbind.$(OBJEXT)
am_libqdp_a_OBJECTS = qdp_map.$(OBJEXT) qdp_subset.$(OBJEXT) \
	qdp_random.$(OBJEXT) qdp_layout.$(OBJEXT) qdp_io.$(OBJEXT) \
	qdp_byteorder.$(OBJEXT) qdp_util.$(OBJEXT) qdp_stdio.$(OBJEXT) \
	qdp_profile.$(OBJEXT) qdp_strnlen.$(OBJEXT) \
	qdp_crc32.$(OBJEXT) qdp_stopwatch.$(OBJEXT) \
	qdp_rannyu.$(OBJEXT) $(am__objects_1) $(am__objects_2) \
	$(am__objects_3) $(am__objects_4) $(am__objects_5) \
	$(am__objects_6) $(am__objects_7) $(am__objects_8) \
	$(am__objects_9) $(am__objects_10) $(am__objects_11)
libqdp_a_OBJECTS = $(am_libqdp_a_OBJECTS)
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)/include
depcomp = $(SHELL) $(top_srcdir)/config/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
AM_V_CXX = $(am__v_CXX_$(V))
am__v_CXX_ = $(am__v_CXX_$(AM_DEFAULT_VERBOSITY))
am__v_CXX_0 = @echo "  CXX     " $@;
am__v_CXX_1 = 
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) \
	-o $@
AM_V_CXXLD = $(am__v_CXXLD_$(V))
am__v_CXXLD_ = $(am__v_CXXLD_$(AM_DEFAULT_VERBOSITY))
am__v_CXXLD_0 = @echo "  CXXLD   " $@;
am__v_CXXLD_1 = 
SOURCES = $(libqdp_a_SOURCES)
DIST_SOURCES = $(am__libqdp_a_SOURCES_DIST)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
# Read a list of newline-separated strings from the standard input,
# and print each of them once, without duplicates.  Input order is
# *not* preserved.
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
# Make sure the list of sources is unique.  This is necessary because,
# e.g., the same source file might be shared among _SOURCES variables
# for different programs/libraries.
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/missing aclocal-1.14
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 1
AR = ar
ARCH_SITE = scalarsite
AUTOCONF = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/missing autoconf
AUTOHEADER = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/missing autoheader
AUTOMAKE = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/missing automake-1.14
AWK = gawk
BAGEL_QDP_CONFIG = 
BAGEL_QDP_CXXFLAGS = 
BAGEL_QDP_LDFLAGS = 
BAGEL_QDP_LIBS = 
CONFIG_ALIGNMENT = 16
CONFIG_GENERICS = yes
CONFIG_HDF5 = 
CONFIG_LAYOUT = cb2
CONFIG_NC = 3
CONFIG_ND = 4
CONFIG_NS = 4
CONFIG_PARALLEL_ARCH = scalar
CONFIG_PRECISION = 32
CONFIG_SSE = 
CONFIG_SSE2 = 
CONFIG_SSE3 = 
CPPFLAGS = -I/fast/space/projects/dr002/dc-kash1/qdpxx/../c-lime/build/include -L/fast/space/projects/dr002/dc-kash1/qdpxx/../c-lime/build/lib64
CXX = icpc -openmp -std=c++11
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -g -O2
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DOXYGEN = doxygen
DVIPDF = dvipdf
DVIPS = dvips
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EXEEXT = 
FILEDB_DIR = filedb
HDF5_BIN = 
HDF5_CFLAGS = 
HDF5_CXXFLAGS = 
HDF5_LDFLAGS = 
HDF5_LIBS = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LATEX = latex
LDFLAGS = 
LIBINTRIN_DIR = 
LIBOBJS = 
LIBS = 
LIBXML2_CONFIG = /usr/bin/xml2-config
LIBXML2_CXXFLAGS = -I/usr/include/libxml2
LIBXML2_LIBS = -lxml2 -lz -lm
LTLIBOBJS = 
MAKEINFO = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/missing makeinfo
MKDIR_P = /bin/mkdir -p
OBJEXT = o
PACKAGE = qdp--
PACKAGE_BUGREPORT = edwards@jlab.org
PACKAGE_NAME = qdp++
PACKAGE_STRING = qdp++ 1.44.0
PACKAGE_TARNAME = qdp--
PACKAGE_URL = 
PACKAGE_VERSION = 1.44.0
PATH_SEPARATOR = :
QMP_CFLAGS = 
QMP_CONFIG = 
QMP_HOME = 
QMP_LDFLAGS = 
QMP_LIBS = 
QMT_CXXFLAGS = 
QMT_HOME = 
QMT_LDFLAGS = 
QMT_LIBS = 
RANLIB = ranlib
SET_MAKE = 
SHELL = /bin/sh
STRIP = 
VERSION = 1.44.0
abs_builddir = /fast/space/projects/dr002/dc-kash1/qdpxx/lib
abs_srcdir = /fast/space/projects/dr002/dc-kash1/qdpxx/lib
abs_top_builddir = /fast/space/projects/dr002/dc-kash1/qdpxx
abs_top_srcdir = /fast/space/projects/dr002/dc-kash1/qdpxx
ac_ct_CXX = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build_alias = 
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host_alias = 
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /fast/space/projects/dr002/dc-kash1/qdpxx/config/install-sh
libdir = ${exec_prefix}/lib64
libexecdir = ${exec_prefix}/lib
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /fast/space/projects/dr002/dc-kash1/qdpxx/build
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
subdirs =  other_libs/filedb other_libs/qio other_libs/xpath_reader
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
INCFLAGS = -I../include -I../include \
	-I../other_libs/qio/include \
	-I../other_libs/qio/include \
	-I../other_libs/qio/other_libs/c-lime/include \
	-I../other_libs/qio/other_libs/c-lime/include \
	$(am__append_1) $(am__append_2)
AM_CXXFLAGS = $(INCFLAGS)   -I/usr/include/libxml2   
lib_LIBRARIES = libqdp.a
libqdp_a_SOURCES = qdp_map.cc qdp_subset.cc qdp_random.cc \
	qdp_layout.cc qdp_io.cc qdp_byteorder.cc qdp_util.cc \
	qdp_stdio.cc qdp_profile.cc qdp_strnlen.cc qdp_crc32.cc \
	qdp_stopwatch.cc qdp_rannyu.cc $(am__append_3) $(am__append_4) \
	$(am__append_5) $(am__append_6) $(am__append_7) \
	$(am__append_8) $(am__append_9) $(am__append_10) \
	$(am__append_11) $(am__append_12) $(am__append_13)
all: all-am

.SUFFIXES:
.SUFFIXES: .cc .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu lib/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu lib/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
install-libLIBRARIES: $(lib_LIBRARIES)
	@$(NORMAL_INSTALL)
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	list2=; for p in $$list; do \
	  if test -f $$p; then \
	    list2="$$list2 $$p"; \
	  else :; fi; \
	done; \
	test -z "$$list2" || { \
	  echo " $(MKDIR_P) '$(DESTDIR)$(libdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(libdir)" || exit 1; \
	  echo " $(INSTALL_DATA) $$list2 '$(DESTDIR)$(libdir)'"; \
	  $(INSTALL_DATA) $$list2 "$(DESTDIR)$(libdir)" || exit $$?; }
	@$(POST_INSTALL)
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	for p in $$list; do \
	  if test -f $$p; then \
	    $(am__strip_dir) \
	    echo " ( cd '$(DESTDIR)$(libdir)' && $(RANLIB) $$f )"; \
	    ( cd "$(DESTDIR)$(libdir)" && $(RANLIB) $$f ) || exit $$?; \
	  else :; fi; \
	done

uninstall-libLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@list='$(lib_LIBRARIES)'; test -n "$(libdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(libdir)'; $(am__uninstall_files_from_dir)

clean-libLIBRARIES:
	-test -z "$(lib_LIBRARIES)" || rm -f $(lib_LIBRARIES)
scalarsite_sse/$(am__dirstamp):
	@$(MKDIR_P) scalarsite_sse
	@: > scalarsite_sse/$(am__dirstamp)
scalarsite_sse/$(DEPDIR)/$(am__dirstamp):
	@$(MKDIR_P) scalarsite_sse/$(DEPDIR)
	@: > scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/qdp_scalarsite_sse.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/qdp_scalarsite_linalg_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_local_sumsq_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_local_vcdot_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_local_vcdot_real_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vaxmbyz4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vaxmyz4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vaxpbyz4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vaxpy4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vaypx4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_blas_vscal4_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_eq_scal_m_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_peq_m_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_eq_mm_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_eq_mh_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_eq_hm_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
scalarsite_sse/sse_linalg_m_eq_hh_double.$(OBJEXT):  \
	scalarsite_sse/$(am__dirstamp) \
	scalarsite_sse/$(DEPDIR)/$(am__dirstamp)

libqdp.a: $(libqdp_a_OBJECTS) $(libqdp_a_DEPENDENCIES) $(EXTRA_libqdp_a_DEPENDENCIES) 
	$(AM_V_at)-rm -f libqdp.a
	$(AM_V_AR)$(libqdp_a_AR) libqdp.a $(libqdp_a_OBJECTS) $(libqdp_a_LIBADD)
	$(AM_V_at)$(RANLIB) libqdp.a

mostlyclean-compile:
	-rm -f *.$(OBJEXT)
	-rm -f scalarsite_sse/*.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/qdp_bgq_threadbind.Po
include ./$(DEPDIR)/qdp_byteorder.Po
include ./$(DEPDIR)/qdp_crc32.Po
include ./$(DEPDIR)/qdp_default_allocator.Po
include ./$(DEPDIR)/qdp_generic_threadbind.Po
include ./$(DEPDIR)/qdp_hdf5.Po
include ./$(DEPDIR)/qdp_io.Po
include ./$(DEPDIR)/qdp_iogauge.Po
include ./$(DEPDIR)/qdp_layout.Po
include ./$(DEPDIR)/qdp_map.Po
include ./$(DEPDIR)/qdp_map_obj_disk.Po
include ./$(DEPDIR)/qdp_parscalar_init.Po
include ./$(DEPDIR)/qdp_parscalar_layout.Po
include ./$(DEPDIR)/qdp_parscalar_specific.Po
include ./$(DEPDIR)/qdp_parscalarvec_init.Po
include ./$(DEPDIR)/qdp_parscalarvec_layout.Po
include ./$(DEPDIR)/qdp_parscalarvec_specific.Po
include ./$(DEPDIR)/qdp_profile.Po
include ./$(DEPDIR)/qdp_qdpio.Po
include ./$(DEPDIR)/qdp_qio_strings.Po
include ./$(DEPDIR)/qdp_random.Po
include ./$(DEPDIR)/qdp_rannyu.Po
include ./$(DEPDIR)/qdp_scalar_init.Po
include ./$(DEPDIR)/qdp_scalar_layout.Po
include ./$(DEPDIR)/qdp_scalar_specific.Po
include ./$(DEPDIR)/qdp_scalarsite_specific.Po
include ./$(DEPDIR)/qdp_scalarvec_init.Po
include ./$(DEPDIR)/qdp_scalarvec_layout.Po
include ./$(DEPDIR)/qdp_scalarvec_specific.Po
include ./$(DEPDIR)/qdp_scalarvecsite_specific.Po
include ./$(DEPDIR)/qdp_scalarvecsite_sse.Po
include ./$(DEPDIR)/qdp_stdio.Po
include ./$(DEPDIR)/qdp_stopwatch.Po
include ./$(DEPDIR)/qdp_strnlen.Po
include ./$(DEPDIR)/qdp_subset.Po
include ./$(DEPDIR)/qdp_util.Po
include ./$(DEPDIR)/qdp_xmlio.Po
include scalarsite_sse/$(DEPDIR)/qdp_scalarsite_linalg_double.Po
include scalarsite_sse/$(DEPDIR)/qdp_scalarsite_sse.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_local_sumsq_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_local_vcdot_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_local_vcdot_real_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vaxmbyz4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vaxmyz4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vaxpbyz4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vaxpy4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vaypx4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_blas_vscal4_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_eq_hh_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_eq_hm_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_eq_mh_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_eq_mm_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_eq_scal_m_double.Po
include scalarsite_sse/$(DEPDIR)/sse_linalg_m_peq_m_double.Po

.cc.o:
	$(AM_V_CXX)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.o$$||'`;\
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ $< &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(AM_V_CXX_no)$(CXXCOMPILE) -c -o $@ $<

.cc.obj:
	$(AM_V_CXX)depbase=`echo $@ | sed 's|[^/]*$$|$(DEPDIR)/&|;s|\.obj$$||'`;\
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $$depbase.Tpo -c -o $@ `$(CYGPATH_W) '$<'` &&\
	$(am__mv) $$depbase.Tpo $$depbase.Po
#	$(AM_V_CXX)source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(AM_V_CXX_no)$(CXXCOMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags

tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am

CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am

cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i"; \
	  else \
	    echo "$$sdir/$$i"; \
	  fi; \
	done >> $(top_builddir)/cscope.files

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LIBRARIES)
installdirs:
	for dir in "$(DESTDIR)$(libdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
	-rm -f scalarsite_sse/$(DEPDIR)/$(am__dirstamp)
	-rm -f scalarsite_sse/$(am__dirstamp)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libLIBRARIES mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR) scalarsite_sse/$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-libLIBRARIES

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR) scalarsite_sse/$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-libLIBRARIES

.MAKE: install-am install-strip

.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-libLIBRARIES cscopelist-am ctags ctags-am distclean \
	distclean-compile distclean-generic distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-libLIBRARIES install-man \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-compile mostlyclean-generic pdf pdf-am ps ps-am \
	tags tags-am uninstall uninstall-am uninstall-libLIBRARIES


# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
