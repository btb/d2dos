#
# $Source: f:/miner/source/2d/rcs/makefile $
# $Revision: 1.44 $
# $Author: matt $
# $Date: 1996/12/04 18:52:36 $
#
# Makefile for bios functions
#

# What to install, and where to install it
INSTALL_TARGS = effect2d.h gr.h gr.lib grdef.h gr.inc palette.h ibitblt.h rle.h pcx.h

# What to clean
CLEAN_TARGS = $(OBJDIR)\*.obj

# What libs to make
LIBS = gr

# What test programs to make
#TEST_PROGS = testg testp vesatest
#PROGS = testg

# What object files for the lib
GR_OBJS = linear.obj canvas.obj bitmap.obj gr.obj font.obj &
	bitblt.obj scanline.obj pixel.obj poly.obj disc.obj rect.obj box.obj  &
	gpixel.obj line.obj lbitblt.obj	   &
	scale.obj scalea.obj circle.obj ibitblt.obj rle.obj pcx.obj
#effects.obj roller.obj 

# What object files and libs for the test programs
#TESTG_SRCS = testg.c tmapbits.c
#TESTG_LIBS = io.lib gr.lib misc.lib mem.lib iff.lib  cfile.lib

#TESTP_OBJS = testp.obj
#TESTP_LIBS = io.lib gr.lib misc.lib mem.lib cflib.lib 

#VESATEST_OBJS = vesatest.obj
#VESATEST_LIBS = io.lib gr.lib misc.lib mem.lib cflib.lib 

#rules and targets common to all Miner makefiles
!include ..\..\init\wmake.def

