###############################################################
#   Students' Makefile for Operating Systems Project          #
#                     Use As Is                               #
###############################################################


# The default C compiler 
C_COMP = cc 


#make OSP:  

OSP : osp.o dialog.o devices.o 
	$(C_COMP) osp.o dialog.o devices.o  -lm -g -o OSP

dialog.o : dialog.c
	$(C_COMP) -c -g dialog.c

devices.o : devices.c 
	$(C_COMP) -c -g devices.c 
