
slides.pdf: slides.tex beamerthemeTU.sty sec_nix.tex sec_git.tex sec_python.tex
	lualatex slides.tex
	lualatex slides.tex

show: slides.pdf
	mimeopen slides.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf slides.pdf
