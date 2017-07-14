### computational physics thesis on human social structures
This is the repository for my doctorate thesis entitled:
"Topological stability and textual differentiation in human
interaction networks: statistical analysis, visualization and linked data"

#### obtaining the PDF from the Latex source files
The final document is thesis-rfabbri.pdf

For obtaining it from the source files, run:
  $ pdflatex USPSC-modelo-IFSC-DFA.tex
  $ cp USPSC-modelo-IFSC-DFA.tex thesis-rfabbri.pdf
  $ cp USPSC-modelo-IFSC-DFA.tex tese-rfabbri.pdf # backward compatibility, old links...


In the old days we obtained the final DF with:
  $ pdftk A=USPSC-modelo-IFSC-DFA.pdf B=referencias_.pdf cat A1-104 B A117-end output tese-rfabbri.pdf

The ./referencias_.pdf document with the bibliography is obtained from ./notes/Referencias\ Renato\ Fabbri_.docx
(might need to add margins 3cm left on odd pages, 3cm right on even pages, and the page numbering)
