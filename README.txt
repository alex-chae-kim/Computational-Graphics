To compile and run simpleTexture.cpp

1. Change the following paths in the Makefile to wherever glfw and glew are installed on your machine (should work out of the box if you are on mac):
-I/opt/homebrew/opt/glew/include \
-I/opt/homebrew/opt/glfw/include
-L/opt/homebrew/opt/glew/lib \
-L/opt/homebrew/opt/glfw/lib \

2. Navigate to the Assignment-1 directory
3. Run ./run.sh