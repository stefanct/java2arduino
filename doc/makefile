RESINPUT=to_include/
RESOUTPUT= $(wildcard *-out/)

.PHONY:	all, clean

all:
	$(foreach dir,$(RESOUTPUT),cp -a $(RESINPUT)* $(dir) ;)
	doxygen

clean:
	$(foreach dir,$(RESOUTPUT),rm -rf $(dir)* ;)
