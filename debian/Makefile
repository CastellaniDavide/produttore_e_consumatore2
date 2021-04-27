prefix = /usr/local

all:
	$(CC) -o produttore_e_consumatore2 produttore_e_consumatore2.c

install:
	gcc -o produttore_e_consumatore2 produttore_e_consumatore2.c
	echo $(DESTDIR)
	echo $(prefix)
	install produttore_e_consumatore2 $(DESTDIR)$(prefix)/bin
	install produttore_e_consumatore2.1 $(DESTDIR)$(prefix)/share/man/man1

clean:
	rm -f produttore_e_consumatore2
