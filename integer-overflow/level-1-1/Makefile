TARGET = integer-overflow-level1.1
CC     = gcc
CFLAGS = -Wall -Wextra -Werror
SECFLAGS = -no-pie -fno-stack-protector

.PHONY: all clean

all: $(TARGET)

%: %.c
	$(CC) $(CFLAGS) $(SECFLAGS) -o $@ $<

clean: 
	rm -rf $(TARGET)
