MAIN=main
BIB=bibliography
all:
	pdflatex $(MAIN).tex
	bibtex $(MAIN)
	pdflatex $(MAIN).tex
	pdflatex $(MAIN).tex
clean:
	rm *.log *.nav *.out *.toc *.aux *.snm *.vrb *.bbl *.blg *.xml $(MAIN)-blx.bib