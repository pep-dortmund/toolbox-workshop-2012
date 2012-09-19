
script.pdf: script.tex
	lualatex --shell-escape script.tex
	lualatex --shell-escape script.tex

show: script.pdf
	mimeopen script.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf script.pdf
