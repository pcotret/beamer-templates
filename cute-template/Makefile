all:
	lualatex -synctex=1 -shell-escape -interaction=nonstopmode main.tex
clean:
	rm *.aux *.log  *.nav *.out *.snm *.synctex.gz *.toc *.listing *.vrb
	rm -r _minted-main
clean_pdf:
	rm main.pdf
clean_all: clean clean_pdf
