FILENAME=main
BIBNAME=bibliography

all:
	pdflatex ${FILENAME}.tex
	bibtex ${FILENAME}
	pdflatex ${FILENAME}.tex
	pdflatex ${FILENAME}.tex
clean:
	rm *.aux *.bbl *.blg *.log *.out *.snm *.toc *.vrb *.xml main-blx.bib *.nav
clean_pdf:
	rm ${FILENAME}.pdf
clean_all: clean clean_pdf