cc = gcc
target = animal
objects = dog.o blackcow.o turtle.o main.o


$(target): $(objects)
	$(cc) -o $(target) $(objects)

$(objects) : animal.h

clean :
	rm *.o animal
.PHONY: clean
