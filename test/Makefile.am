AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS=symhash_test
symhash_test_SOURCES=symhash_test.cc
symhash_test_LDADD = -lgtest -lgtest_main -lpthread \
                     $(top_srcdir)/src/libsymhash.a 
