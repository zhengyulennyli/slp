Service Learning Practicum
==========================

The Service Learning Practicum course (CS 4970/4971) at the University
of Virginia.  Content will be added to this repo throughout the 2014
calendar year.

Repository Contents
-------------------

None of these links will work if being viewed on github.com; you will
have to clone (or otherwise download) the repository.

- [Slides](slides/index.html)
- [Lectures](lectures.html)


Markdown
--------

The majority of the content in this repository was created using
Markdown.  Unfortunately, the only standardized Markdown is very old
(2004), and has limited support for many HTML features, such as
tables.  Indeed, the default Ubuntu version of Markdown is the 2004
version.  To address this, a [markdown.c](utils/markdown.c.html)
([src](utils/markdown.c)) program was written to use more recent
Markdown features.  This program uses the libmarkdown library, which
does support more recent Markdown features.  This library installed on
Ubuntu via the 'libmarkdown2-dev' package.  Note that reveal.js, which
is used for the slides, also supports more modern Markdown features.
That being said, the extra Markdown features used in this repository
should be compatible with the generally accepted Markdown features.

To compile: "gcc markdown.c -o markdown -lmarkdown". To use, specify
the input file name, and optionally an output file.  The resulting
document is a full HTML document -- meaning it adds the doctype, html,
head, and body tags to the document, as necessary.

For all the Markdown files, both the original (.md) file and the HTML
version (.html) are added to the repository, so that people who do not
have Markdown installed can still view the contents of this
repository.



