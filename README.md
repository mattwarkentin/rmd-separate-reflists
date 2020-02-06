`R Markdown` Document with Separate References
================

**Author:** Matt Warkentin (<warkentin@lunenfeld.ca>)

**Date Updated:** 2020-02-06

This repository houses a `LaTeX` template, skeleton `R Markdown`
document, and a `LaTeX` header file, which allows for separate reference
lists when rendering a `rmarkdown::pdf_document()`. These documents were
developed to solve for a question posted on the `RStudio` Community
forum
[here](https://community.rstudio.com/t/use-citation-in-r-markdown-to-automatically-generate-a-bibliography-of-r-packages/51363).

# Download

The easiest way to get these documents onto your computer would be to
`git clone` this repository locally. To do this in a terminal, navigate
to a conspicous directory and clone, like so:

    # Home directory
    cd ~
    git clone https://github.com/mattwarkentin/rmd-separate-reflists.git

Or, if you use the `RStudio` IDE, you can clone this repo into a `R
Project` by `File > New Project... > Version Control > Git` and paste
this: `https://github.com/mattwarkentin/rmd-separate-reflists.git` into
the repository URL.

# Usage

The usage is straightforward, simply write your document in the `Rmd`
file as you usually would. Include all `BibTeX` citations in the
`refs.bib` file (if you may store citations across multiple `.bib` files
and add them to the YAML header), and cite them as you normally would.

The only other file you will need to edit is the `header.tex` file. In
this file, you may custom-define any reference categories you like, and
assign the `BibTeX` IDs to the various categories. IDs can belong to
multiple categories, if you would like them to show up in multiple
reference lists.

-----

Please note that the ‘rmd-separate-reflists’ project is released with a
[Contributor Code of Conduct](CODE_OF_CONDUCT.md). By contributing to
this project, you agree to abide by its terms.
