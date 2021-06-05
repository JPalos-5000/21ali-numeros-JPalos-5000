#Makefile
all: numeros
@@Esta regla compila el programa principal 
numeros: numeros.o
	ld -o $@ $+
numeros.o: numeros.s
	as -g -mfpu=vfpv2 -o  $@ $+
	@@no tiene dependecias
clean:
	rm -vf numeros *.o


