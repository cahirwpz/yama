LATEX := latexmk -pdf
OUTPUT := komeda.pdf

all: $(OUTPUT)

%.pdf: %.tex %.bib
	$(LATEX) $<

clean:
	latexmk -f -C $(OUTPUT)
	rm -f *~ *.bbl
