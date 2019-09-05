---
layout: project
type: project
image: images/oprPhoto.jpg
title: Air Force EPR Editing Tool
permalink: projects/EprOpr
# All dates must be YYYY-MM-DD format!
date: 2018-12-01
labels:
  - Lisp
  - GitHub
summary: Acronym formatting tool for for Air Force personnel writing an Enlisted Performance Report (EPR).
---

Cotton is a horror-esque text-based adventure game I developed using the functions and macros built from The Wizard's Game in [Conrad Barski's Land of Lisp](http://landoflisp.com/). Slightly more interesting and convoluted! (It is not that scary.)

To give you a flavor of the game, here is an excerpt from one run:

<hr>

<pre>

An Air Force EPR is a form used by supervisors to rate their subordinate's career accomplishments for that year. There is a section where the writer is supposed to write bullet points summarizing the major accomplishments. The problem is that these bullets need to be formatted in such a way that they only take up one line's worth of space and leave little to no whitespace at the end of each line. This forces the writer to use approved acronyms and abbreviate commonly used words that aren't normally abbreviated when writing standard English. 

The EPR Editing Tool gives the user a text box so type out the bullet and select a unit approved acronyms and abbreviations spreadsheet. When the evaluate button is pressed, the software will parse through that bullet and shorten words or sets of words that are in the approved spreadsheet. The program will continue to do so until the entire line of text can fit within the specified specified pixel width. To help prevent the user from typing too many words, there is a progress bar showing the remaining space available. Also, after a word is typed into the text box, a list of synonyms is displayed for that word. This allows the user to further minimize the amount of characters needed to convey the information, and allows the writer to avoid having to reference an external thesaurus.  

A prototype was submitted as a proof-of-concept and was given to Air Force personnel for initial testing and feedback. Some changes were made, but there are more features that need to be added. This program was originally written using Java and the GUI was made using Java's JavaFX platform. It is a downloadable package that works with both Windows and Linux based operating systems. However, shortly after this program was written, Oracle released a new version of Java that no longer supported JavaFX. Therefore, this project will be redone in JavaScript and will be released as an unclassified website.

</pre>

<hr>

Source: <a href="https://github.com/jogarces/ics-313-text-game"><i class="large github icon "></i>jogarces/ics-313-text-game</a>

