# VIEWER and DOC set by parent makefile

render: build
	open -a $(VIEWER) $(DOC).pdf

build:
	latex $(DOC)
	pdflatex $(DOC)

clean:
	rm $(DOC).aux
	rm $(DOC).dvi
	rm $(DOC).log
	rm $(DOC).out

.PHONY: build render
