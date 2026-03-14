# Compiler
CXX = g++

# Compiler flags
CXXFLAGS = -Wall -Wextra -std=c++17

# Source files
SRC = main.cpp Animals.cpp Zoo.cpp


# Header files
HEADERS = Animals.h

# Output executable
TARGET = animals_app

# Default build rule
all: $(TARGET)

# Link and build the final executable
$(TARGET): $(SRC) $(HEADERS)
	$(CXX) $(CXXFLAGS) $(SRC) -o $(TARGET)

# Clean up build files
clean:
	rm -f $(TARGET)

# Run the program
run: $(TARGET)
	./$(TARGET)