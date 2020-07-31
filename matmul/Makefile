CC=gcc
CFLAGS=-g -Wall
LFLAGS=-lOpenCL


all: matmul

matmul: main.c
	$(CC) $(CFLAGS) $(LFLAGS) $< -o $@

clean	:	
	rm matmul
