PROJECT_NAME = STATIC_LIB


SRC = test.c
Inc = Iinc
LDFLAGS = -lmystring -lmyutils - lbitmask -lsrc

$(PROJECT_NAME).out : $(SRC)
	gcc $^ -o $Q $(INC) $(LDFLAGS)

run: $(PROJECT_NAME).out

	./$^
libraries:
	make -C src
clean:
	rm -rf *.o *.out
