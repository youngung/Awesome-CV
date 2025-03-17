#TC=xelatex
TC=latex
DST=~/repo/youngung.github.io/images/


# doc: cv.tex awesome-cv.cls fontawesome.sty fonts Makefile
#	$(TC) cv.tex
#	$(TC) cv_latex.tex
cv: cv_latex.tex
	$(TC) cv_latex.tex
	cp cv_latex.pdf $(DST)/cv.pdf

# copy: cv.pdf
#	cp cv.pdf $(DST)
