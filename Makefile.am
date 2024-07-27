AUTOMAKE_OPTIONS = subdir-objects

bin_PROGRAMS = hallo
hallo_SOURCES = src/main.c src/file1.c src/file2.c

check_PROGRAMS = test_main
test_main_SOURCES = tests/test_main.c
test_main_LDADD = -lcheck -lm -lsubunit

