CC=gcc

all: $@.c

$@.c: $@.o
	$(CC) -o $@ $p

$@.o: $@.c
	$(CC) -c $<

clean:
	rm -f *.out *.o