#########################################################################
#                                                                       #
# Copyright 2014 Adobe Systems Incorporated.                       #
# All rights reserved.                                                  #
#                                                                       #
#########################################################################

# Configuration
CONFIG = debug
CFLAGS = $(STD_OPTS) -g

# Library
ROOT_DIR = ../../../../..
SRC_DIR = $(ROOT_DIR)/source/varread
aa
LIB_SRCS = $(SRC_DIR)/varread.c
LIB_OBJS = varread.o
LIB_TARGET = $(LIB_DIR)/varread.a

# Build targets
TARGETS = $(LIB_TARGET)
# Standard definitions
include ../../../../../config/linux/gcc/gcc_tx.mak

# Object rules
varread.o:
	$(CC) $(CFLAGS) -c $(SRC_DIR)/varread.c -o $@
