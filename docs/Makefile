
pdf-pandoc: studie.md metodika.md
	~/.cabal/bin/pandoc \
		--smart \
		-t latex \
		-o opendata.pdf \
		--template="pt.tex" \
		meta.md studie.md metodika.md

pdf-mmd: studie.md metodika.md
	multimarkdown \
		--full \
		--smart \
		-o all.tex -t latex \
		studie.md metodika.md
	#xelatex all.tex

clean:
	rm -rf *.log
