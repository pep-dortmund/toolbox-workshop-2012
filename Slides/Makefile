
slides.pdf: slides.tex beamerthemeTU.sty sec_intro.tex sec_unix.tex sec_git.tex sec_python.tex sec_libraries.tex
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
