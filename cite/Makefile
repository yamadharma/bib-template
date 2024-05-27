fixbib:
	cp ../bib/main.bib .
	./fixbib.sh
	-pandoc main.bib -t csljson -o main.json
	-bibtex-tidy --no-escape --duplicates key --merge --enclosing-braces=title,subtitle,journal *.bib

