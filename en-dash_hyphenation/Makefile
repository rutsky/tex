# Makefile
# Simple building latex document Makefile.
# Vladimir Rutsky <altsysrq@gmail.com>
# 22.03.2009

SOURCE  = en-dash_hyphenation_test
TEX2PDF = pdflatex

all: $(SOURCE).pdf

$(SOURCE).pdf: $(SOURCE).tex
	$(TEX2PDF) $(SOURCE).tex

clean:
	rm -f $(SOURCE).aux
	rm -f $(SOURCE).log

distclean: clean
	rm -f $(SOURCE).pdf

