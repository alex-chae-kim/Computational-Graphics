CXX := g++
CXXFLAGS := -std=c++17 \
	-I../external/glm \
	-I/opt/homebrew/opt/glew/include \
	-I/opt/homebrew/opt/glfw/include

LDFLAGS := \
	-L/opt/homebrew/opt/glew/lib \
	-L/opt/homebrew/opt/glfw/lib \
	-lGLEW \
	-lglfw \
	-framework OpenGL

TARGET := simpleTexture
SRC := simpleTexture.cpp

all: $(TARGET)

$(TARGET): $(SRC)
	$(CXX) $(SRC) $(CXXFLAGS) $(LDFLAGS) -o $(TARGET)

clean:
	rm -f $(TARGET)
