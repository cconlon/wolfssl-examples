CC=gcc
CFLAGS=-Wall
WOLFSSL_INSTALL_DIR=/usr/local
LIBS=-L$(WOLFSSL_INSTALL_DIR)/lib -lwolfssl

3des-file-encrypt: 3des-file-encrypt.o
	$(CC) -o $@ $^ $(CFLAGS) $(LIBS) 

.PHONY: clean

clean:
	rm -f *.o 3des-file-encrypt
