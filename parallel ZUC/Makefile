CC=g++
CFLAGS=-c -Wall

SOURCES= ZUC.cpp main.cpp
OBJECTS=$(SOURCES:.cpp=.o)
EXECUTABLE=prog_p

all: $(SOURCES) $(EXECUTABLE) clean

$(EXECUTABLE): $(OBJECTS)
	$(CC) $(LDFLAGS) $(OBJECTS) -o $@

.cpp.o:
	$(CC) $(CFLAGS) $< -o $@

clean:
	rm *.o
