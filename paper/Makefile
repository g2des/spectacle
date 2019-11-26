all: paper.pdf


paper.pdf: paper.tex
	pdflatex paper.tex
	pdflatex paper.tex
	bibtex paper
	pdflatex paper.tex
	pdflatex paper.tex


clean: 
	rm -f *.pdf *.ps *.dvi *.log *.aux *.bbl *.blg *.snm *.toc
