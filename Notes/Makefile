
notes.pdf: notes.tex header.tex sec_intro.tex sec_unix.tex sec_git.tex sec_python.tex
	lualatex --shell-escape notes.tex
	lualatex --shell-escape notes.tex

show: notes.pdf
	mimeopen notes.pdf

clean:
	rm -rf *.log
	rm -rf *.out
	rm -rf *.toc
	rm -rf *.snm
	rm -rf *.aux
	rm -rf *.nav
	rm -rf *.vrb
	rm -rf notes.pdf
	rm -rf *.pyg
