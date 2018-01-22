CC      = gcc -g -O0 -Wall
LIBS    = -lm

OBS	= main.o key.o romnums.o globals.o
HEADERS	= key.h

key: $(OBS)
	$(CC) $(OBS) $(LIBS) -o key

$(OBS):	$(HEADERS)

clean: 
	rm -f *.o *~
	echo "Project cleaned."
