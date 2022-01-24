#
# Student makefile for Cache Lab
# Note: requires a 64-bit x86-64 system 
#
CC = gcc
CFLAGS = -g -Wall  -std=gnu99 -m64

all: cache 

cache: cache.c print.c print.h
	$(CC) $(CFLAGS) -o $@ cache.c print.c -lm 

#
# Clean the src dirctory
#
clean:
	rm -rf *.o
	rm -f cache
	rm -f trace.all trace.f*
	rm -f .csim_results .marker
