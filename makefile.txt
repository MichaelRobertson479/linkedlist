all: linkedlist.o
gcc -o list linkedlist.o

linkedlist.o: linkedlist.c
gcc -c linkedlist.c

run:
./list