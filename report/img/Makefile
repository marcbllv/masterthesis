SRC  = $(wildcard /Users/marcbeillevaire/Documents/kth/masterthesis/report/img/*.svg)
TRGT = $(SRC:.svg=.pdf)

all: $(TRGT)

%.pdf: %.svg 
	inkscape -D -z --file=$^ --export-pdf=$@ --export-latex

clean:
	rm -rf *.pdf_tex
	rm -rf *.pdf
