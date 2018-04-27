#
#
#

all: nl soap

nl: nl.c
	cc -o nl nl.c

soap: soap.c unpack.c
	cc -o soap -g soap.c unpack.c
