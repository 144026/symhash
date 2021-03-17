AM_CPPFLAGS = -I$(top_srcdir)/include

noinst_PROGRAMS=symhash_bench
symhash_bench_SOURCES=symhash_bench.cc
symhash_bench_LDADD = -lbenchmark -lpthread ../src/libsymhash.la
