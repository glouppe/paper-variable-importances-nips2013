nips.pdf: bib.bib nips.tex nips-suppl.tex
	pdflatex -shell-escape nips
	pdflatex -shell-escape nips-suppl
	bibtex nips
	bibtex nips-suppl
	pdflatex -shell-escape nips
	pdflatex -shell-escape nips-suppl
	pdflatex -shell-escape nips
	pdflatex -shell-escape nips-suppl

clean:
	rm -f *.log *.out *.aux *.bbl *.blg nips-pics.pdf nips.pdf nips-suppl.pdf 
