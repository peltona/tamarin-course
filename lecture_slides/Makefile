LECTURE=0
LECTURES=0 1 2 3 4 5 6 7 8 9

# Create PDF for one lecture
# e.g., make LECTURE=1
lecture:
	pdflatex lecture_${LECTURE}
	biber lecture_${LECTURE}
	pdflatex lecture_${LECTURE}
	mv lecture_${LECTURE}.pdf ./slides/

quick:
	pdflatex lecture_${LECTURE}
	pdflatex lecture_${LECTURE}
	mv lecture_${LECTURE}.pdf ./slides/

# Create PDFs for all lectures
all:
	for L in ${LECTURES}; do\
		pdflatex lecture_$$L;\
		biber lecture_$$L;\
		pdflatex lecture_$$L;\
		mv lecture_$$L.pdf ./slides/;\
	done;

clean:
	rm -f ./*.aux
	rm -f ./*.bbl
	rm -f ./*.bcf
	rm -f ./*.blg
	rm -f ./*.nav
	rm -f ./*.out
	rm -f ./*.snm
	rm -f ./*.toc
	rm -f ./*.upa
	rm -f ./*.vrb
	rm -f ./*.log
	rm -f ./*.xml
