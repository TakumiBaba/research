all:
	platex    -kanji=sjis main
	# pbibtex   -kanji=sjis main
	platex    -kanji=sjis main
	platex    -kanji=sjis main
	dvipdfmx  -p a4 main
	open      main.pdf
clean:
	/bin/rm -f *~ *.log *.dvi *.blg *.aux *.out *.bbl *.lot *.toc *.lof *.pdf
