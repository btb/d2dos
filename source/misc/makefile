#
# $Source: f:/miner/source/misc/rcs/makefile $
# $Revision: 1.7 $
# $Author: matt $
# $Date: 1996/01/23 22:32:42 $
#
# Makefile for misc libaray
#

# What to install
INSTALL_TARGS = misc.lib parsarg.h debug.h hash.h args.h byteswap.h

# What libs to build
LIBS = misc

# What objs in the lib
MISC_OBJS = parsarg.obj hash.obj args.obj

# What to clean
CLEAN_TARGS = $(OBJDIR)\*.obj

# What test programs to make
TEST_PROGS = errtest parstest

# What object files and libs for the test programs
PARSTEST_SRCS = parstest.c
PARSTEST_LIBS = misc.lib

ERRTEST_SRCS = errtest.c
ERRTEST_LIBS = misc.lib

#rules and targets common to all Miner makefiles
!include ..\..\init\wmake.def

