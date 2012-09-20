
script.pdf: script.tex header.tex
	lualatex --shell-escape script.tex
	lualatex --shell-escape script.tex

show: notes.pdf
	mimeopen script.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf *.vrb
	rm -rf script.pdf
	rm -rf *.pyg
