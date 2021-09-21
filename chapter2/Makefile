targets = 2_2_1_1 2_2_1_1.s
CFLAGS = -O3
LDFLAGS = -pthread

all: $(targets)

%.s: %.c
	$(CC) -O3 -S $<

.PHONY: clean
clean:
	rm -f $(targets)
