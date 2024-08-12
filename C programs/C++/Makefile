# Makefile for a simple C++ program

# Name of the executable
TARGET = hello_world

# Source files
SRCS = hello_world.cpp

# Compiler
CXX = g++

# Compiler flags
CXXFLAGS = -std=c++17 -Wall

# Linker flags (if any)
LDFLAGS =

# Build rule
$(TARGET): $(SRCS)
	$(CXX) $(CXXFLAGS) $(SRCS) -o $(TARGET) $(LDFLAGS)

# Clean rule
clean:
	rm -f $(TARGET)
