# Latex markdown template

This repository is a small collection of:

1. Personal templates for use with latex or markdown
2. Python scripts to automate the populating process

Each directory contains a working template and example PDF output.

## Python scripts

Python scripts are used to automate the population of latex files.

## Markdown/Latex Templates

Use for short documentation of topics, lecture notes or exam preparation notes.  
For bigger reports either use one of the report templates.

## Latex templates

Latex templates for personal use.

## Requirements

### Software

Be sure to have LaTeX ([Windows](http://miktex.org/), [OS X](https://tug.org/mactex/),
[Linux](http://latex-project.org/)), Pandoc and Python installed.

On macOS, Pandoc can be installed with Homebrew: `brew install pandoc`.

### Compiling

1. If you use markdown, you can use either use the `Makefile` with `make` or just use `pandoc` for typesetting.
2. If you write the file in latex you can use the python script to generate the latex file, populate it and covert it with the `pdf-latex` engine for pdf conversion.

For the `report-bib` you will need `pandoc-citeproc` too. On macOS that is easily installed with
`brew install pandoc-citeproc`.

## Customization

If you want to see what Pandoc allows for customization you can use `pandoc -D latex` to get the
default LaTeX template. You can set variables with `-V/--variable` when using `pandoc` or preferably
put them into a [YAML front matter](http://assemble.io/docs/YAML-front-matter.html).

## Acknowledge

### Useful ressources

Some useful resources, that gave me great informations:

#### Blog posts

1. https://jabranham.com/blog/2015/09/rmarkdown-vs-latex/
2. https://uoftcoders.github.io/studyGroup/lessons/misc/pandoc-intro/lesson/
3. https://jabranham.com/blog/2015/09/version-control/
4. https://tech.lauritz.me/easy-latex-with-markdown-pandoc/
5. http://blog.poormansmath.net/how-to-take-lecture-notes-with-latex/
6. https://vijual.de/wp-content/uploads/2018/11/Artikel-schreiben-mit-Markdown_0.1.4.pdf
7. https://vijual.de/2018/11/07/artikel-mit-markdown-und-pandoc-schreiben/
8. https://afnan.io/2018-09-02/beautiful-pdfs-from-your-markdown-notes/
9. http://ricardo.ecn.wfu.edu/~cottrell/wp.html
10. https://ericphanson.com/blog/2016/live-notetaking-with-latex/
11. https://www.physicsforums.com/threads/learning-latex-and-note-taking.828033/
12. https://www.reddit.com/r/LaTeX/comments/3h5um6/latex_for_college_notetakinghomework/
13. https://www.quora.com/Does-anybody-use-LaTeX-to-take-notes-especially-during-class-If-not-what-do-you-use-especially-when-you-need-to-write-down-equations
14. https://tex.stackexchange.com/questions/95677/a-good-template-for-note-taking

#### Tutorials

1. http://www.uweziegenhagen.de/wp-content/uploads/2013/08/LaTeX_and_Python.pdf
2. https://superuser.com/questions/511900/why-doesnt-my-symbolic-link-work
3. https://slhck.info/documents/pa.wgi_tutorial1.pdf

#### Latex-Python

1. http://akuederle.com/Automatization-with-Latex-and-Python-1

#### Templates

1. https://github.com/jgm/pandoc/wiki/User-contributed-templates
2. https://github.com/aaronwolen/pandoc-letter
3. https://github.com/daniel-vera-g/pandoc-latex-template
4. https://www.zotero.org/
5. https://github.com/lauritzsh/pandoc-markdown-template

#### Editor

1. https://texwelt.de/wissen/fragen/884/welcher-latex-editor-fur-einsteiger-empfehlenswert
2. https://en.wikipedia.org/wiki/TeXworks
2. https://wiki.ubuntuusers.de/Kile/
