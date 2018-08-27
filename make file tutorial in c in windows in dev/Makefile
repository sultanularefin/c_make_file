# Project: Project1
# Makefile created by Dev-C++ 4.9.9.2

CPP  = g++
CC   = gcc

RES  = 
OBJ  = main.o hello.o factorial.o $(RES)
LINKOBJ  = main.o hello.o factorial.o $(RES)
LIBS =  -L"/usr/lib"  
INCS =  -I"/usr/include" 
CXXINCS =  -I"C:/Dev-Cpp/lib/gcc/mingw32/3.4.2/include"  -I"/usr/include/c++/4.8/"  -I"C:/ 
CXXFLAGS = $(CXXINCS)  
CFLAGS = $(INCS)  
RM = rm -f

.PHONY: all all-before all-after clean clean-custom

all: all-before Project1all-after


clean: clean-custom
	${RM} $(OBJ) $(BIN)

$(BIN): $(OBJ)
	$(CC) $(LINKOBJ) -o Project1 $(LIBS)

main.o: main.c
	$(CC) -c main.c -o main.o $(CFLAGS)

hello.o: hello.c
	$(CC) -c hello.c -o hello.o $(CFLAGS)

factorial.o: factorial.c
	$(CC) -c factorial.c -o factorial.o $(CFLAGS)
