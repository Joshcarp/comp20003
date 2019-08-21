# -*- Makefile -*-
# target:dependencies	
helloworld: helloworld.o another.o
	gcc -Wall helloworld.o another.o -o helloworld

helloworld.o: helloworld.c
	gcc -Wall helloworld.c -o helloworld.o

another.o: another.c
	gcc -Wall another.c -o another.o
