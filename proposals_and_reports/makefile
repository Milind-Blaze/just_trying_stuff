.PHONY: all
all: LIGO_proposal

LIGO_proposal: %: %.tex
	latexmk -f -pdf $@

.PHONY: clean 

clean:
	latexmk -c 

.PHONY: cleanall

cleanall:
	latexmk -C