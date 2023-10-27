main: main.o chunk.o memory.o debug.o value.o vm.o compiler.o scanner.o object.o table.o
	gcc -O -Wall -pedantic -ansi -std=c99 -o main main.o chunk.o memory.o debug.o value.o vm.o compiler.o scanner.o object.o table.o

main.o: memory.o
	gcc -O -Wall -pedantic -ansi -std=c99 -c main.c

chunk.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c chunk.c

memory.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c memory.c

debug.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c debug.c

value.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c value.c

vm.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c vm.c

compiler.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c compiler.c

scanner.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c scanner.c

object.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c object.c

table.o:
	gcc -O -Wall -pedantic -ansi -std=c99 -c table.c

clean:
	rm *.o