SRC_DIR = .
TARGET = vm
CFLAGS = -I. -std=c99 -Wall -Werror -Wextra -ggdb $(shell pkg-config --cflags sdl2) -I..
LDFLAGS = $(shell pkg-config --libs sdl2)
CFILES += ../lib/log.c

include ../template.mk
