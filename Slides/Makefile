
vortrag.pdf: vortrag.tex
	lualatex vortrag.tex
	lualatex vortrag.tex

show: vortrag.pdf
	mimeopen vortrag.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf vortrag.pdf
