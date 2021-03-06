
########### next target ###############

SET(t_skeleton_SRCS
   t_skeleton.cc
)

add_executable(t_skeleton ${t_skeleton_SRCS})

target_link_libraries(t_skeleton)


########### next target ###############

SET(t_io_SRCS
   t_io.cc
   $(HDRS)
)

add_executable(t_io ${t_io_SRCS})

target_link_libraries(t_io)


########### next target ###############

SET(t_mesplq_SRCS
   t_mesplq.cc
   mesplq.cc
   reunit.cc
   $(HDRS)
)

add_executable(t_mesplq ${t_mesplq_SRCS})

target_link_libraries(t_mesplq)


########### next target ###############

SET(t_db_SRCS
   t_db.cc
   $(HDRS)
)

add_executable(t_db ${t_db_SRCS})

target_link_libraries(t_db)


########### next target ###############

SET(t_xml_SRCS
   t_xml.cc
   $(HDRS)
)

add_executable(t_xml ${t_xml_SRCS})

target_link_libraries(t_xml)


########### next target ###############

SET(t_entry_SRCS
   t_entry.cc
   $(HDRS)
)

add_executable(t_entry ${t_entry_SRCS})

target_link_libraries(t_entry)


########### next target ###############

SET(t_nersc_SRCS
   t_nersc.cc
   mesplq.cc
   reunit.cc
   $(HDRS)
)

add_executable(t_nersc ${t_nersc_SRCS})

target_link_libraries(t_nersc)


########### next target ###############

SET(t_shift_SRCS
   t_shift.cc
   $(HDRS)
)

add_executable(t_shift ${t_shift_SRCS})

target_link_libraries(t_shift)


########### next target ###############

SET(t_exotic_SRCS
   t_exotic.cc
   rgauge.cc
   taproj.cc
   expm12.cc
   reunit.cc
   $(HDRS)
)

add_executable(t_exotic ${t_exotic_SRCS})

target_link_libraries(t_exotic)


########### next target ###############

SET(t_basic_SRCS
   t_basic.cc
)

add_executable(t_basic ${t_basic_SRCS})

target_link_libraries(t_basic)


########### next target ###############

SET(t_qio_SRCS
   t_qio.cc
   $(HDRS)
)

add_executable(t_qio ${t_qio_SRCS})

target_link_libraries(t_qio)


########### next target ###############

SET(t_cugauge_SRCS
   t_cugauge.cc
   mesplq.cc
   $(HDRS)
)

add_executable(t_cugauge ${t_cugauge_SRCS})

target_link_libraries(t_cugauge)


########### next target ###############

SET(t_transpose_spin_SRCS
   t_transpose_spin.cc
   $(HDRS)
)

add_executable(t_transpose_spin ${t_transpose_spin_SRCS})

target_link_libraries(t_transpose_spin)


########### next target ###############

SET(t_partfile_SRCS
   t_partfile.cc
   $(HDRS)
   unittest.h
   testOpenPartFile.h
)

add_executable(t_partfile ${t_partfile_SRCS})

target_link_libraries(t_partfile)


########### next target ###############

SET(t_su3_SRCS
   t_su3.cc
)

add_executable(t_su3 ${t_su3_SRCS})

target_link_libraries(t_su3)


########### next target ###############

SET(t_map_obj_disk_SRCS
   t_map_obj_disk.cc
   $(HDRS)
)

add_executable(t_map_obj_disk ${t_map_obj_disk_SRCS})

target_link_libraries(t_map_obj_disk)


########### next target ###############

SET(t_map_obj_memory_SRCS
   t_map_obj_memory.cc
   $(HDRS)
)

add_executable(t_map_obj_memory ${t_map_obj_memory_SRCS})

target_link_libraries(t_map_obj_memory)


########### next target ###############

SET(t_clov_force_SRCS
   t_clov_force.cc
   reunit.cc
   $(HDRS)
)

add_executable(t_clov_force ${t_clov_force_SRCS})

target_link_libraries(t_clov_force)


########### next target ###############

SET(t_qio_factory_SRCS
   t_qio_factory.cc
   $(HDRS)
)

add_executable(t_qio_factory ${t_qio_factory_SRCS})

target_link_libraries(t_qio_factory)


########### next target ###############

SET(t_gsum_SRCS
   t_gsum.cc
)

add_executable(t_gsum ${t_gsum_SRCS})

target_link_libraries(t_gsum)


########### next target ###############

SET(t_iprod_SRCS
   t_iprod.cc
)

add_executable(t_iprod ${t_iprod_SRCS})

target_link_libraries(t_iprod)


########### install files ###############




#original Makefile.am contents follow:

##
## Boiler Plate stuff: Autoconf Substitutions etc
##
### Should only need @QMP_CFLAGS@, @QMP_LDFLAGS@ and @QMP_LIBS@
### n.b. Only defined for some parallel architectures
#AM_CXXFLAGS = -I@top_srcdir@/include -I@top_builddir@/include \
#              -I@top_srcdir@/other_libs/qio/include \
#	      -I@top_builddir@/other_libs/qio/include \
#              -I@top_srcdir@/other_libs/qio/other_libs/c-lime/include \
#              -I@top_builddir@/other_libs/qio/other_libs/c-lime/include \
#              -I@top_srcdir@/other_libs/xpath_reader/include \
#              @BAGEL_QDP_CXXFLAGS@ @HDF5_CXXFLAGS@ @LIBXML2_CXXFLAGS@ @QMP_CFLAGS@ @QMT_CXXFLAGS@
#
#if BUILD_LIBINTRIN
#AM_CXXFLAGS += -I@top_srcdir@/other_libs/@LIBINTRIN_DIR@/include \
#               -I@top_builddir@/other_libs/@LIBINTRIN_DIR@/include
#endif
#
#if BUILD_FILEDB
#AM_CXXFLAGS += -I@top_srcdir@/other_libs/filedb/src \
#               -I@top_srcdir@/other_libs/filedb/filehash
#endif
#
#AM_LDFLAGS = -L@top_builddir@/lib
#
#if QDP_USE_LIBXML2
#AM_LDFLAGS += -L@top_builddir@/other_libs/qio/lib \
#             -L@top_builddir@/other_libs/qio/other_libs/c-lime/lib \
#             -L@top_builddir@/other_libs/xpath_reader/lib
#endif
#AM_LDFLAGS += @LDFLAGS@ @BAGEL_QDP_LDFLAGS@ @HDF5_LDFLAGS@ @QMP_LDFLAGS@ @QMT_LDFLAGS@
#
#if BUILD_LIBINTRIN
#AM_LDFLAGS += -L@top_builddir@/other_libs/libintrin/lib
#endif
#
#if BUILD_FILEDB
#AM_LDFLAGS += -L@top_builddir@/other_libs/filedb/src \
#              -L@top_builddir@/other_libs/filedb/filehash
#endif
#
#LDADD = -lqdp
#
#if QDP_USE_HDF5
#LDADD += @HDF5_LIBS@
#endif
#
#if QDP_USE_LIBXML2
#LDADD += -lXPathReader -lxmlWriter -lqio -llime
#endif
#LDADD += @BAGEL_QDP_LIBS@ @LIBXML2_LIBS@ @QMP_LIBS@ @QMT_LIBS@ @LIBS@
#
#if BUILD_LIBINTRIN
#LDADD += -lintrin
#endif
#
#if BUILD_FILEDB
#LDADD += -lfiledb -lfilehash
#endif
#
##
## Local Headers
##
#HDRS=examples.h 
#
##
## The programs to build
## 
#check_PROGRAMS = t_skeleton t_io t_mesplq t_db \
#      t_xml t_entry t_nersc t_shift t_exotic t_basic t_qio \
#      t_cugauge t_transpose_spin t_partfile t_su3 \
#      t_map_obj_disk t_map_obj_memory t_clov_force
#
#EXTRA_PROGRAMS  = t_qio_factory t_gsum t_iprod
#
#
#if BUILD_WILSON_EXAMPLES
#check_PROGRAMS += t_dslashm t_formfac t_spectrum t_qdp t_linalg 
#EXTRA_PROGRAMS += t_subtype t_foo t_blas t_cblas t_blas_g5 t_blas_g5_2 t_blas_g5_3 t_spinproj t_spinproj2
#endif
#
#EXTRA_PROGRAMS += nersc2ildg test_ildglat lhpc2ildg
#
#if BUILD_STAGGERED_EXAMPLES
#check_PROGRAMS += 
#endif
#
##
## The program and its dependencies
#t_skeleton_SOURCES = t_skeleton.cc
#t_foo_SOURCES = t_foo.cc $(HDRS)
#t_subtype_SOURCES = t_subtype.cc $(HDRS)
#t_xml_SOURCES = t_xml.cc $(HDRS)
#t_qio_SOURCES = t_qio.cc $(HDRS)
#t_qio_DEPENDENCIES = build_lib rebuild_other_libs
#t_qio_factory_SOURCES = t_qio_factory.cc $(HDRS)
#t_qio_factory_DEPENDENCIES = build_lib rebuild_other_libs
#t_partfile_SOURCES = t_partfile.cc $(HDRS) \
#	unittest.h testOpenPartFile.h
#t_partfile_DEPENDENCIES = build_lib rebuild_other_libs
#
#t_basic_SOURCES = t_basic.cc
#t_shift_SOURCES = t_shift.cc $(HDRS)
#t_io_SOURCES = t_io.cc $(HDRS)
#t_entry_SOURCES = t_entry.cc $(HDRS)
#t_nersc_SOURCES = t_nersc.cc mesplq.cc reunit.cc $(HDRS)
#t_dslashm_SOURCES = t_dslashm.cc dslashm_w.cc $(HDRS)
#t_mesplq_SOURCES = t_mesplq.cc mesplq.cc reunit.cc $(HDRS)
#t_exotic_SOURCES = t_exotic.cc rgauge.cc taproj.cc expm12.cc reunit.cc $(HDRS)
#t_formfac_SOURCES = t_formfac.cc formfac_w.cc $(HDRS)
#t_spectrum_SOURCES = t_spectrum.cc baryon_w.cc mesons_w.cc mesplq.cc $(HDRS)
#t_qdp_SOURCES =  t_qdp.cc formfac_w.cc dslashm_w.cc baryon_w.cc \
#	 mesons_w.cc mesplq.cc reunit.cc $(HDRS)
#t_linalg_SOURCES =  t_linalg.cc linalg1.cc linalg.h
#
#t_blas_SOURCES = t_blas.cc blas1.cc blas1.h
#t_blas_DEPENDENCIES = build_lib
#
#t_gsum_SOURCES = t_gsum.cc
#t_gsum_DEPENDENCIES = build_lib
#
#t_iprod_SOURCES = t_iprod.cc
#t_iprod_DEPENDENCIES = build_lib
#
#t_cblas_SOURCES= t_cblas.cc cblas1.cc cblas1.h 
#
#t_clov_force_SOURCES=t_clov_force.cc reunit.cc $(HDRS)
#t_clov_force_DEPENDENCIES= build_lib
#
#t_db_SOURCES = t_db.cc $(HDRS)
#t_map_obj_disk_SOURCES = t_map_obj_disk.cc $(HDRS)
#t_map_obj_memory_SOURCES = t_map_obj_memory.cc $(HDRS)
#
#t_blas_g5_SOURCES = t_blas_g5.cc $(HDRS)
#t_blas_g5_2_SOURCES = t_blas_g5_2.cc $(HDRS)
#t_blas_g5_3_SOURCES = t_blas_g5_3.cc $(HDRS)
#t_spinproj_SOURCES = t_spinproj.cc 
#t_spinproj2_SOURCES = t_spinproj2.cc 
#
#t_cugauge_SOURCES = t_cugauge.cc mesplq.cc $(HDRS) 
#t_transpose_spin_SOURCES = t_transpose_spin.cc $(HDRS)
#
#nersc2ildg_SOURCES = nersc2ildg.cc $(HDRS) mesplq.cc
#test_ildglat_SOURCES = test_ildglat.cc $(HDRS) mesplq.cc
#test_ildglat_DEPENDENCIES = build_lib
#
#t_su3_SOURCES = t_su3.cc 
#t_su3_DEPENDENCIES = build_lib
#
#lhpc2ildg_SOURCES = lhpc2ildg.cc $(HDRS) mesplq.cc
#lhpc2ildg_DEPENDENCIES = build_lib
#
## build lib is a target that goes tot he build dir of the library and 
## does a make to make sure all those dependencies are OK. In order
## for it to be done every time, we have to make it a 'phony' target
#.PHONY: build_lib
#build_lib:
#	cd @top_builddir@/lib ; $(MAKE)
#
#.PHONY: rebuild_other_libs
#rebuild_other_libs:
#	cd @top_builddir@/other_libs ; $(MAKE)
