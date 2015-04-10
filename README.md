# UT-Austin Dissertation/Thesis LaTeX Template

updated by: Dan Garrette (dhg@cs.utexas.edu)

This passed inspection by the graduate school in Spring 2015.

## How to use:

Edit the following files:

    abstract.tex      % put abstract here
    main.tex          % put all content here
    packages.tex      % preable stuff here
    thesis.bib        % bibtex entries
    utthesis2015.tex  % edit to fill in fields (committee member names, etc)

Compile the document

    pdflatex utthesis2015.tex
    pdflatex utthesis2015.tex
    bibtex utthesis2015.aux
    bibtex utthesis2015.aux
    pdflatex utthesis2015.tex
    pdflatex utthesis2015.tex

If you want a "draft" version (small margins, single spaced, no title page, etc), the compile the `draft.tex` file instead of `utthesis2015`.


