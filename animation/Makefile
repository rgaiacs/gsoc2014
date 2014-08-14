################################### PROGRAMS ###################################
PNG2GIF = convert
PNG2GIFFLAGS = -set delay 50 -loop 0

################################### VARIABLE ###################################
ANIMATIONS = alternate.gif \
	     auto-capitalization.gif \
	     backspace.gif dots.gif \
	     jumps.gif \
	     script-continue.gif \
	     script-new.gif \
	     styled-letters.gif

##################################### RULE #####################################
all: $(ANIMATIONS)

%.gif:
	$(PNG2GIF) $(subst .gif,*.png, $@) $(PNG2GIFFLAGS) $@
