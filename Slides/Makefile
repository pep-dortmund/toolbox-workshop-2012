
slides.pdf: slides.tex beamerthemeTU.sty sec_nix.tex sec_git.tex sec_python.tex
	lualatex --shell-escape slides.tex
	lualatex --shell-escape slides.tex

show: slides.pdf
	mimeopen slides.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf *.vrb
	rm -rf slides.pdf
