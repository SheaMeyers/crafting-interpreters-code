main: main.o chunk.o memory.o debug.o value.o vm.o
	gcc -o main main.o chunk.o memory.o debug.o value.o vm.o

main.o: main.c chunk.h memory.h
	gcc -c main.c

chunk.o: chunk.c chunk.h
	gcc -c chunk.c

memory.o: memory.c memory.h
	gcc -c memory.c

debug.o: debug.c debug.h
	gcc -c debug.c

value.o: value.c value.h
	gcc -c value.c

vm.o: vm.c vm.h
	gcc -c vm.c
