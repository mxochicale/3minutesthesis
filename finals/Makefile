SLIDES=README

all: $(SLIDES).pdf


%.pdf : %.md
	pandoc $< -o $@

clean:
	rm *.pdf 
