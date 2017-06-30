CC = gcc
#Using -Ofast instead of -O3 might result in faster code, but is supported only by newer GCC versions
CFLAGS = -lm -pthread -O3 -march=native -Wall -funroll-loops -Wno-unused-result

all: tewv_1

tewv_1 : tewv_1.c
	$(CC) tewv_1.c -o tewv_1 $(CFLAGS)


