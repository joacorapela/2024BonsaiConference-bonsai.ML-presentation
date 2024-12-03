all: bonsaiML.pdf

%.pdf: %.tex introduction.tex linearRegression.tex 
	pdflatex $<
	bibtex $*.aux
	pdflatex $<
	pdflatex $<

