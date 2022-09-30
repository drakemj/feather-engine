CC=g++
SRC_DIR=.
GUI_DIR=imgui
OUT=gui
LINKERS=-lSDL2
INCLUDE=-I../include
LIBRARIES=-L../lib/lib

build:
	$(CC) $(SRC_DIR)/*.cpp $(GUI_DIR)/*.cpp $(LINKERS) $(INCLUDE) $(LIBRARIES) -o $(OUT)
