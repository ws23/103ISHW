main: src/main.o aes.o
	gcc src/main.o src/aes.o -o XTS-AES.exe

main.o: src/aes.h src/main.c
	gcc -c main.c -o src/main.o

aes.o: src/aes.h src/aes.c
	gcc -c src/aes.c -o src/aes.o

# clean
clean: 
	rm src/*.o XTS-AES.exe
