NAME=WG3
ALL=${NAME}.pdf

all: ${ALL}

%.pdf: %.tex
	pdflatex $<

clean:
	rm -f ${NAME}.snm ${NAME}.nav ${NAME}.log ${NAME}.out ${NAME}.snm \
		${NAME}.toc ${NAME}.aux
