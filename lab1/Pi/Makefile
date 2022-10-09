EXECS=pi-c pi-mpi
CFLAGS=-Wall
LDFLAGS=-lm
MPICC=mpicc
CC=gcc
all: ${EXECS}
pi-mpi: pi-mpi.c
	${MPICC} -o pi-mpi pi-mpi.c ${CFLAGS} ${LDFLAGS}
clean:
	rm -f ${EXECS}
