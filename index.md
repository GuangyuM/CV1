Johnny Coder
============

-------------------     ----------------------------
1 MyAddress                        email@example.com
MyTown 1000                          @twitter_handle
MyCountry                           1800 my-phone-nr
-------------------     ----------------------------

Education
---------

2010-2014 (expected)
:   **PhD, Computer Science**; Awesome University (MyTown)

    *Thesis title: Deep Learning Approaches to the Self-Awesomeness
     Estimation Problem*

2007-2010
:   **BSc, Computer Science and Electrical Engineering**; University of
    HomeTown (HomeTown)

    *Minor: Awesomeology*

Experience
----------

**Your Most Recent Work Experience:**

Short text containing the type of work done, results obtained,
lessons learned and other remarks. Can also include lists and
links:

* First item

* Item with [link](http://www.example.com). Links will work both in
  the html and pdf versions.

**That Other Job You Had**

Also with a short description.

Technical Experience
--------------------

My Cool Side Project
:   For items which don't have a clear time ordering, a definition
    list can be used to have named items.

    * These items can also contain lists, but you need to mind the
      indentation levels in the markdown source.
    * Second item.

Open Source
:   List open source contributions here, perhaps placing emphasis on
    the project names, for example the **Linux Kernel**, where you
    implemented multithreading over a long weekend, or **node.js**
    (with [link](http://nodejs.org)) which was actually totally
    your idea...

Programming Languages
:   **first-lang:** Here, we have an itemization, where we only want
    to add descriptions to the first few items, but still want to
    mention some others together at the end. A format that works well
    here is a description list where the first few items have their
    first word emphasized, and the last item contains the final few
    emphasized terms. Notice the reasonably nice page break in the pdf
    version, which wouldn't happen if we generated the pdf via html.

:   **second-lang:** Description of your experience with second-lang,
    perhaps again including a [link] [ref], this time placing the url
    reference elsewhere in the document to reduce clutter (see source
    file). 

:   **obscure-but-impressive-lang:** We both know this one's pushing
    it.

:   Basic knowledge of **C**, **x86 assembly**, **forth**, **Common Lisp**

[ref]: https://github.com/githubuser/superlongprojectname

Extra Section, Call it Whatever You Want
----------------------------------------

* Human Languages:

     * English (native speaker)
     * ???
     * This is what a nested list looks like.

* Random tidbit

* Other sort of impressive-sounding thing you did
---
output: 
  pdf_document:
    latex_engine: pdflatex
    template: ~/Dropbox/miscelanea/svm-r-markdown-templates/svm-latex-cv.tex
geometry: margin=1in

title: "CV"
author: William Sealy Gosset

jobtitle: "Chief Brewer, Arthur Guinness & Son"
address: "Guinness Brewery · Park Royal · London NW10 7RR, UK"
fontawesome: yes
email: guinness@consumer-care.net
# github: svmiller
phone: "+353 1 408 4800"
web: guinness.com
updated: no

keywords: R Markdown, academic CV, template

fontfamily: mathpazo
fontfamilyoptions: sc, osf
fontsize: 11pt
linkcolor: blue
urlcolor: blue
---
<!DOCTYPE html>
<html>
<title>Hello Strapdown</title>

<xmp theme="cerulean" style="display:none;">

# 把刚刚Markdown的文本放在这里就可以啦

</xmp>

<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>
</html>

