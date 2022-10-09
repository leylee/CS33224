EXECS=mpi_hello_world
MPICC=mpicc
CFLAGS=-Wall
LDFLAGS=-lm
all: ${EXECS}
mpi_hello_world: mpi_hello_world.c
	${MPICC} -o mpi_hello_world mpi_hello_world.c ${CFLAGS} ${LDFLAGS}
clean:
	rm -f ${EXECS}
