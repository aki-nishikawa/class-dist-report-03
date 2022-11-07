CC = gcc

all:	tcp_server.out tcp_client.out

tcp_server.out:	tcp_server.c
	$(CC) $< -o $@

tcp_client.out:	tcp_client.c
	$(CC) $< -o $@

clean:
	rm *.out *.txt

PHONY: all clean