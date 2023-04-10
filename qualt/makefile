paper_main.pdf: paper_main.tex aaai23.bib
	pdflatex paper_main.tex
	bibtex paper_main
	pdflatex paper_main.tex
	pdflatex paper_main.tex
clean:
	rm -f paper_main.aux paper_main.bbl paper_main.blg paper_main.log paper_main.pdf
