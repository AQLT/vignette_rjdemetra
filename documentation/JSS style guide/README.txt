***************************************************
** jss: A Document Class for Publications in the **
**        Journal of Statistical Software        **
***************************************************

This zip-archive contains the pdfLaTeX infrastructure for publications
in the Journal of Statistical Software. The files
  - jss.cls (LaTeX2e class)
  - jss.bst (BibTeX style)
  - jsslogo.jpg (JPG logo)
need to be included in your search path (local working directory, texmf
or localtexmf tree).

A manual how to use jss.cls is provided in
  - jss.pdf.

Detailed instructions on how to use the jss document class are given on
https://www.jstatsoft.org/pages/view/style, where we provide templates
for the different submission types.

JSS papers should be prepared using JSS styles; the submission of the
final version needs to include the full sources (.tex, .bib, and all
graphics). A quick check for the most important aspects of the JSS style
is given below; authors should make sure that all of them are addressed
in the final version:
  - The manuscript can be compiled by pdfLaTeX.
  - \proglang, \pkg and \code have been used for highlighting throughout
    the paper (including titles and references), except where explicitly
    escaped.
  - References are provided in a .bib BibTeX database and included in
    the text by \cite, \citep, \citet, etc.
  - Titles and headers are formatted as described in the JSS manual:
      - \title in title style,
      - \section etc. in sentence style,
      - all titles in the BibTeX file in title style.
  - Figures, tables and equations are marked with a \label and referred
    to by \ref, e.g., "Figure~\ref{...}".
  - Software packes are \cite{}d properly.
For more details, see the style FAQ at
https://www.jstatsoft.org/pages/view/style and the manual jss.pdf, in
particular the style checklist in Section 2.1.
