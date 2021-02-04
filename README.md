# Purpose

This document is for students who are writing a thesis at the Computer Vision Group of the University of Stuttgart.
It contains general rules for writing theses with LaTex in a computer science or math department, along with more specific formatting rules that should be followed especially in our group.

The source code for the document may help you if you want to know how the pdf file was produced.


# Compiling

Compile the document with

    pdflatex -interaction=batchmode template.tex
    bibtex template.aux
    pdflatex -interaction=batchmode template.tex
    pdflatex -interaction=batchmode template.tex

**Important:** If your output pdf document does not look like the supplied pdf file, your Tex Live version is probably too old.
At the time of writing, this document was compiled with

* pdfTeX [Version 3.14159265-2.6-1.40.20]
* TeX Live 2019
* BibTeX [Version 0.99d]


# Maintenance

Please report any typos or other issues to Jenny Schmalfuss (jenny.schmalfuss [at] vis.uni-stuttgart.de)


# Source of Latex Template

Created by Torsten Moeller, April 6 2004
modified by Steven Bergner and Torsten Moeller, June 30 2006
modified by James Peltier and Torsten Moeller, March 28, 2007
modified by Martin Falk, March 03, 2010
modified by Jenny Schmalfuss, October 01, 2020

This distribution provides a document class for formatting papers
according to the specifications for submission to conferences sponsored by
the IEEE Visualization & Graphics Technical Committee (VGTC).

The distribution was adapted to the specifications for seminars at
the Institute for Visualization and Interactive Systems, 
University of Stuttgart.
