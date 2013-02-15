all: report.pdf

report.pdf: report.tex bibliography.bib
	pdflatex report.tex && bibtex report && pdflatex report.tex && pdflatex report.tex

clean:
	rm -f report.{aux,log,bbl,blg}
