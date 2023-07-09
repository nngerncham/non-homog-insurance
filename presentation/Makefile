all:
	marp --allow-local-files --html --pdf Presentation.md -o Presentation.pdf --theme themes/academic.css

watch:
	zathura Presentation.pdf &
	marp -w --allow-local-files --html --pdf Presentation.md -o Presentation.pdf --theme themes/academic.css

present:
	marp -s . --allow-local-files --html --theme themes/academic.css

clean:
	rm -rf *.pdf
