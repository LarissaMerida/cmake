# Makefile
# especifico

test: main.o div.o
#test depende de main.o div.o

#produzido
	g++ main.o div.o -o test

#main.o produzido
main.o: main.cpp div.h
	g++ -c main.cpp

#mesmo com  div
div.o: div.cpp div.h
	g++ -c div.cpp