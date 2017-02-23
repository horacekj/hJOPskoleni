# Change content of this variable to match filename
TARGET = chyby

all: $(TARGET).pdf

$(TARGET).pdf: $(TARGET).tex
	pdflatex $^

clean:
	rm -rf $(TARGET).aux $(TARGET).log $(TARGET).out $(TARGET).nav $(TARGET).snm $(TARGET).vrb $(TARGET).toc

pdfclean: clean
	rm -rf $(TARGET).pdf

