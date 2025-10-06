# BUILD

PDF with jupyter book

eg: jb build --toc _toc_island_misc.yml --builder pdflatex .

spellchecker --files  *.md --dictionaries rce-dictionary.txt  > spellingreport.txt



---


brew install imagemagick



pandoc tea-tales-logo.md -o teatales_logo.pdf --pdf-engine=xelatex

magick -density 300 teatales_logo.pdf teatales_logo.png

magick -density 300  teatales_logo.pdf -alpha off teatales_logo.png