.PHONY: all

all: pdf

pdf: newsletter.tex
		latexmk -pdf -recorder -pdflatex="pdflatex -interactive=nonstopmode" -use-make newsletter.tex

clean:
		rm -fv *.aux *.bbl *.blg *.log *.nav *.out *.snm *.toc *.dvi *.vrb *.bcf *.run.xml *.cut *.lo* *.brf*
			latexmk -c

