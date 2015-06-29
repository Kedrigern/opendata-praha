
pdf-pandoc: studie.md metodika.md
	~/.cabal/bin/pandoc \
		--smart \
		-t latex \
		--latex-engine=xelatex \
		-o opendata.pdf \
		meta.md studie.md metodika.md
# default template:
# https://github.com/jgm/pandoc-templates/blob/master/default.latex

pdf-mmd: studie.md metodika.md
	multimarkdown \
		--full \
		--smart \
		-o all.tex -t latex \
		studie.md metodika.md
	#xelatex all.tex

clean:
	rm -rf *.log
