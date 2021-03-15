%.pdf: %.tex
	latexmk -pdf -pdflatex="pdflatex -interaction=nonstopmode" -use-make $<
	$(MAKE) clean

clean:
	rm -f *.aux
	rm -f *.log
	rm -f *.fdb_latexmk
	rm -f *.fls
	rm -f *.synctex.gz
	rm -f *.out
	rm -f *.toc
	rm -f *.pre
