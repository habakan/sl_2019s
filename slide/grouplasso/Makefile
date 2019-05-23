.SUFFIXES: .tex .dvi .pdf

all: main.pdf

clean:
	rm -rf *.aux *.dvi *.log *.nav *.snm *.toc *.out

.tex.dvi:
	platex $<

.dvi.pdf:
	dvipdfmx $<

main.pdf: main.tex main.dvi
