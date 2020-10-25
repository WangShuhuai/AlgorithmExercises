GCC=gcc
main:main.o
	$(GCC) -o $@ $?
main.o:main.c
	$(GCC) -c $^
.PYONY:clean
clean:
	rm main.o main
