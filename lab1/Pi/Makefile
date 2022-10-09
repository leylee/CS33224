EXECS=pi-c pi-mpi
MPICC=mpicc
CC=gcc
all: ${EXECS}
pi-mpi: pi-mpi.c
	${MPICC} -o pi-mpi pi-mpi.c
clean:
	rm -f ${EXECS}
