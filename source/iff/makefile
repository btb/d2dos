#
# $Source: f:/miner/source/iff/rcs/makefile $
# $Revision: 1.5 $
# $Author: john $
# $Date: 1994/02/15 12:51:20 $
#
# Makefile for IFF library
#

# What to install
INSTALL_TARGS = iff.lib iff.h

# What libs to build
LIBS = iff

# What objs in the iff lib
IFF_OBJS = iff.obj

# What test programs to make
TEST_PROGS = ifftest ifftestv

# What object files and libs for the test programs
IFFTEST_SRCS = ifftest.c
IFFTEST_LIBS = iff.lib vga.lib gr.lib mem.lib misc.lib cfile.lib io.lib

IFFTESTV_SRCS = ifftestv.c
IFFTESTV_LIBS = iff.lib vesa.lib cflib.lib cfile.lib

#rules and targets common to all Miner makefiles
!include ..\..\init\wmake.def

