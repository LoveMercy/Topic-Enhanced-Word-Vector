CC = gcc
#Using -Ofast instead of -O3 might result in faster code, but is supported only by newer GCC versions
CFLAGS = -lm -pthread -O3 -march=native -Wall -funroll-loops -Wno-unused-result

all: tewv_3

tewv_3 : tewv_3.c
	$(CC) tewv_3.c -o tewv_3 $(CFLAGS)


