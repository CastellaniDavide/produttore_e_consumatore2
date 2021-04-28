prefix = /usr/local

all:
	$(CC) -o produttoreconsumatore2 produttoreconsumatore2.c

install:
	gcc -o produttoreconsumatore2 produttoreconsumatore2.c
	echo $(DESTDIR)
	echo $(prefix)
	install produttoreconsumatore2 $(DESTDIR)$(prefix)/bin
	install produttoreconsumatore2.1 $(DESTDIR)$(prefix)/share/man/man1

clean:
	rm -f produttoreconsumatore2
