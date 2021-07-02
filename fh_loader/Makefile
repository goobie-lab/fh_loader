CC = gcc

CFLAGS = -w -D_FILE_OFFSET_BITS=64

SRCS = fh_loader.cpp fh_loader_sha.cpp
BIN = fh_loader

all: $(BIN)

$(BIN): $(SRCS)
	gcc $(CFLAGS) $^ -o $@

clean:
	rm -f $(BIN)
