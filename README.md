# UT-Austin Dissertation/Thesis LaTeX Template

Updated by: Dan Garrette (dhg@cs.utexas.edu).  See the comments in `utthesis2015.sty` for the long list of people who have worked on this before.

This passed inspection by the graduate school in Spring 2015.

You can download all the files as a `zip` file by clicking the "Download ZIP" button on the right ->

Please email me or submit a pull request if you have improvements or contributions.


## How to use it:

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


