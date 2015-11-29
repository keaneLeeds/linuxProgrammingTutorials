OBJ = main.o reciprocal.o
INC = ../include/

reciprocal: $(OBJ)
		g++ $(CFLAGS) -o reciprocal $(OBJ)

main.o: main.c $(INC)
		gcc $(CFLAGS) -c -I $(INC) main.c

reciprocal.o: reciprocal.cpp $(INC)
		g++ $(CFLAGS) -c -I $(INC) reciprocal.cpp

.PHONY: clean
clean:
		rm -f $(OBJ) reciprocal Makefile~
