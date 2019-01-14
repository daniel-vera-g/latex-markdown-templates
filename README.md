# Latex markdown template

This repository is a small collection of personal markdown templates for Pandoc and python scripts to automate the compiling process.

Each directory contains a working template and example PDF output.

## Requirements

### Software

Be sure to have LaTeX ([Windows](http://miktex.org/), [OS X](https://tug.org/mactex/),
[Linux](http://latex-project.org/)), Pandoc and Python installed.

On macOS, Pandoc can be installed with Homebrew: `brew install pandoc`.

### Compiling

1. If you use markdown, you can use either use the `Makefile` with `make` or just use `pandoc` for typesetting.
2. If you write the file in latex you can use the python script to generate the latex file, populate it and covert it with the `pdf-latex` engine for pdf conversion.

TODO
<--
For the `report-bib` you will need `pandoc-citeproc` too. On macOS that is easily installed with
`brew install pandoc-citeproc`.
!--> 

## Customization

If you want to see what Pandoc allows for customization you can use `pandoc -D latex` to get the
default LaTeX template. You can set variables with `-V/--variable` when using `pandoc` or preferably
put them into a [YAML front matter](http://assemble.io/docs/YAML-front-matter.html).







































