CC ?= gcc
CFLAGS ?= -ansi -pedantic -Wall -Wextra
CFLAGS_INCLUDE = -I../common/
LDFLAGS ?=

all: cgd2bmp

cgd2bmp: cgd2bmp.c
	$(CC) $(CFLAGS) $(CFLAGS_INCLUDE) -I. $? -o $@ $(LDFLAGS)

clean:
	rm -f cgd2bmp cgd2bmp.exe *.o


.PHONY: clean
