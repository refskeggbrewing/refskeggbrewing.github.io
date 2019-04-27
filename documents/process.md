---
title: Documentation Process
feature_image: /assets/images/document.jpg
---

* * *

## Background 

* * * 

I write my documentation in markdown files and convert to pdf's using
Pandoc and a LaTeX template. As of 27 April, 2019 I have started to use
Chicago style footnote citation for my documentation. It seems to lend
itself a little bit better for historical papers.

This [github repo](https://github.com/m3chanical/scadocs) has several
example files showing how I document my projects. The contents of the
README file are copied here as well. 

On Linux (Ubuntu in my case) with Make, Pandoc and the 
requisite TeXLive packages installed, one may easily be able to
replicate this process. 

The required files are the Makefile, the .latex template, a .md file,
and optionally a logo and references file. These must all be in the same
directory. When the Makefile is executed with `make`, it will use Pandoc
to convert the markdown files into pdfs. 

Using my scadocs repository as an example, please follow below.

### Requirements

Make.
Pandoc installed. (e.g. sudo apt install -y pandoc)
All Latex modules installed. (e.g. sudo apt install -y ...)

    * texlive-binaries
    * texlive-fonts-recommended   
    * texlive-generic-recommended
    * texlive-latex-base
    * texlive-latex-extra
    * texlive-latex-recommended   
    * texlive-pictures

Maybe more Texlive packages. I am never certain... Basically just
install whatever Pandoc gets mad at you for.

### Create Docs

Update the makefile with the new documents (should be pretty straightforward to follow)
Type `make`, which will run pandoc with the latex template.

Indeed Windows users will have to perform different steps for both
Pandoc and LaTeX. However, it can still be done on Windows CLI. I think
Mac will also be similar to Linux (with slight modifications).

Please feel free to email with any questions.


