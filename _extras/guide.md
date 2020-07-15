---
layout: page
title: "Instructor Notes"
---

____
# Tips and Tricks

____
## Making a handout

Adapt/print from:  

* [Library Carpentry Reference Page](https://librarycarpentry.org/lc-open-refine/reference.html)
* [Instructor Draft Notes](https://github.com/LibraryCarpentry/lc-open-refine/blob/gh-pages/files/draft-instructor-notes.md)
* [Introduction to OpenRefine by Owen Stephens](http://www.meanboyfriend.com/overdue_ideas/wp-content/uploads/2014/11/Introduction-to-OpenRefine-handout-CC-BY.pdf)

____
# General notes on OpenRefine

## Common problems

* If learners are using a browser other than Firefox, or OpenRefine does not automatically open for them when they click the .exe file, have them point their browser at http://127.0.0.1:3333/ or http://localhost:3333 to launch the program.

* Mac users with the newest operating system will have to allow this to run by "allowing everything" to run. They can change the setting back after the exercise.

* Some students will run into issues with
  - unzipping
  - finding the .exe file once the software has been unzipped
  - finding the data file on their computers after downloading
  
* If OpenRefine crashes when launched from a network share drive, do the following:
  - Copy the OpenRefine folder to a local drive not mapped to a network share, e.g. "C:\Users\JaneDoe"
  - Open a Windows Command prompt
  - Change the working directory to the OpenRefine folder at "C:\Users\JaneDoe"
  - Run openrefine.exe

* If a learner is unable to install OpenRefine on their computer due to IT restrictions for example, there are cloud services available that they could try:
  - [openrefineder](https://github.com/betatim/openrefineder/) using MyBinder [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/betatim/openrefineder/077bbff?urlpath=%2Fopenrefine) (OpenRefine 3.1, free to use without registration, [restricted](https://mybinder.readthedocs.io/en/latest/faq.html#how-much-memory-am-i-given-when-using-binder) to 1-2 GB RAM and server will be deleted after 10 minutes of inactivity)
  - [openrefineder](https://github.com/betatim/openrefineder/) using MyBinder [![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/betatim/openrefineder/79aeff9?urlpath=%2Fopenrefine) (OpenRefine 3.2, same restrictions as above)
