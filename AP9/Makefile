CC = gcc
LIBS = -lm
SRC = src
OBJ = obj
INC = include
BIN = bin
OBJS = $(OBJ)/avlorig.o 
HDRS = 
CFLAGS = -Wall -c -I$(INC)

EXE = $(BIN)/avlorig

all:  $(EXE)
	$(BIN)/avlorig

$(BIN)/avlorig: $(OBJS)
	$(CC) -g -o $(BIN)/avlorig $(OBJS) $(LIBS)

$(OBJ)/avlorig.o: $(HDRS) $(SRC)/avlorig.c
	$(CC) $(CFLAGS) -o $(OBJ)/avlorig.o $(SRC)/avlorig.c 
	
clean:
	rm -f $(EXE) $(OBJS) gmon.out