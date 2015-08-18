add_subdirectory(@LIBINTRIN_DIR@)
add_subdirectory(@FILEDB_DIR@)


########### install files ###############




#original Makefile.am contents follow:

#SUBDIRS = @LIBINTRIN_DIR@ @FILEDB_DIR@
#if QDP_USE_LIBXML2
#SUBDIRS += qio xpath_reader
#endif
#
#EXTRA_DIST = libintrin filedb
