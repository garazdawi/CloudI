noinst_PROGRAMS = hexpi
hexpi_SOURCES = assert.cpp main.cpp timer.cpp \
                piqpr8_gmp.cpp piqpr8_gmp_verify.cpp
hexpi_CPPFLAGS = -I$(top_srcdir)/api/c/ $(BOOST_CPPFLAGS) \
                 $(GMP_H_CFLAGS)
hexpi_LDFLAGS = $(BOOST_LDFLAGS) $(GMP_LDFLAGS)
hexpi_LDADD = $(top_builddir)/api/c/libcloudi.la \
              $(BOOST_THREAD_LIB) $(BOOST_SYSTEM_LIB) \
              $(GMP_LIB) $(RT_LIB)

