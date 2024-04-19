MAIN=main
BIB=bibliography
all:
	pdflatex -shell-escape $(MAIN).tex
	bibtex $(MAIN)
	pdflatex -shell-escape $(MAIN).tex
	pdflatex -shell-escape $(MAIN).tex
clean:
	rm *.log *.nav *.out *.toc *.aux *.snm *.vrb *.bbl *.blg *.xml $(MAIN)-blx.bib
	rm -rf _minted-main