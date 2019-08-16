
all:	model

clean:
	rm -f *.o
	make all

model:	model.o
	ld -o model model.o

model.o:	model.s
	as -o model.o model.s
