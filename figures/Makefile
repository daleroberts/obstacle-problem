all: fig1-0.png fig2-0.png

%-0.png: %.tex
	pdflatex -shell-escape $^

clean:
	rm -fr *.png *.pdf *.aux *.log
