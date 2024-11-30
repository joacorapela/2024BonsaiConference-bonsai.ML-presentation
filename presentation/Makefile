all: bonsaiML.pdf

%.pdf: %.tex linearRegression.tex
	pdflatex $<
	bibtex $*.aux
	pdflatex $<
	pdflatex $<

