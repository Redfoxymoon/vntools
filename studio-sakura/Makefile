CC ?= gcc
CFLAGS ?= -ansi -pedantic -Wall -Wextra
CFLAGS_INCLUDE = -I../common/
LDFLAGS ?=

all: studio-sakura_unpack

studio-sakura_unpack: studio-sakura_unpack.c cp932.c cp932table.c win32compat.c
	$(CC) $(CFLAGS) $(CFLAGS_INCLUDE) -I. $? -o $@ $(LDFLAGS)

clean:
	rm -f studio-sakura_unpack studio-sakura_unpack.exe *.o


.PHONY: clean
