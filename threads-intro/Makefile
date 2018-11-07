
FLAGS = -Wall -pthread
INCLUDES = ../include

all: t0 t1 t2 t3

clean:
	rm -f t0 t1

t0: t0.c
	gcc -I $(INCLUDES) -o t0 t0.c $(FLAGS)

t1: t1.c
	gcc -I $(INCLUDES) -o t1 t1.c $(FLAGS)


t2: t2.c
	gcc -I $(INCLUDES) -o t2 t2.c $(FLAGS)

t3: t3.c
	gcc -I $(INCLUDES) -o t3 t3.c $(FLAGS)