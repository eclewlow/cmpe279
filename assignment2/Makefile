CC=gcc

all: server client

server: server.o
	$(CC) -o server server.o

client: client.o
	$(CC) -o client client.o

clean:
	rm *.o server client

