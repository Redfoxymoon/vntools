CC ?= gcc
CFLAGS ?= -ansi -pedantic -Wall -Wextra
CFLAGS_INCLUDE = -I../common/
LDFLAGS ?=

all: nekopunch_unpack

nekopunch_unpack: nekopunch_unpack.c cp932.c cp932table.c win32compat.c
	$(CC) $(CFLAGS) $(CFLAGS_INCLUDE) -I. $? -o $@ $(LDFLAGS)

clean:
	rm -f nekopunch_unpack nekopunch_unpack.exe *.o


.PHONY: clean
