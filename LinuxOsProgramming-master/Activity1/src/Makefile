CFLAGS = I../inc

libstr: mystring.o
	ar rc libmystring.a $^

libstr: myutils.o
	ar rc libmyutils.a $^
libstr: bitmask.o
	ar rc libbitmask.a $^
cleam:
	rm -rf *.o *.a
