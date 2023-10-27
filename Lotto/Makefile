# Compiler and flags
CC = gcc
CFLAGS = -Wall -Wextra -std=c99

# Source and header files
SRC = devopsC.c
OBJ = $(SRC:.c=.o)
HEADER = 

# Executable name
EXEC = helloworld

all: $(EXEC)

$(EXEC): $(OBJ)
	$(CC) $(CFLAGS) $(OBJ) -o $(EXEC)

%.o: %.c $(HEADER)
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f $(OBJ) $(EXEC)
