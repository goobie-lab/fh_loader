DESTDIR ?= .

CC = gcc

CFLAGS = -w -D_FILE_OFFSET_BITS=64

SRCS = fh_loader.cpp fh_loader_sha.cpp
BIN = $(DESTDIR)/fh_loader

all: $(BIN)

$(BIN): $(SRCS)
	mkdir -pv $(DESTDIR)
	gcc $(CFLAGS) $^ -o $@

clean:
	rm -f $(BIN)
