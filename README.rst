=========================
Python Learning Resources
=========================

.. contents::

Introduction
============

...


Tibs' original notes
====================

**This is a form of the text that Tibs has been using when asked how to learn
Python.**

Whilst I’m not sure how useful I can be with recomendations on learning
Python, since (a) I did it myself so long ago and since then have “grown with
it”, and (b) I’m not quite sure what your starting position is (knowledge of
PL/I, though, should mean Python isn’t likely to have any *huge* surprises for
you, if I remember rightly), I can definitely try to give some pointers.

The resources I mentioned at CamPUG were:

* https://tutorial.djangogirls.org/en/ - the Django Girls tutorial (boys are
  allowed to use it, too - it says so in the FAQ). This is *probably* too much
  of a beginners text for you, as it starts assuming essentially no computer
  knowledge (it teachs what a command line is, I think). However, one can take
  up at any point in the tutorial. It teaches how to create a web site using
  Django, which is generally useful sort of thing to be abe to do, and a
  fairly concrete thing to aim at.

* https://www.obeythetestinggoat.com/ - this is the “goat book” I
  mentioned. This is ostensibly a book that teaches Test Driven Development in
  Python, which it does (again!) by showing how to create a website with
  Django and associated technologies. This isn’t strictly meant to be an
  introduction to Python itself, but in its insistence that the reader should
  actually type in all the examples, I think it will happen to do that along
  the way. Because it’s not only focussed on Python itself, but Python as part
  of an ecosystem, I think it may be a useful place to start. The online
  version of the book is free, and you can buy it as a paperback if you want
  as well. I find the author’s style quite fun. NB: this is the second
  edition, which is what you want. It’s using Python 3.6, whcih is pretty
  recent. See
  https://www.obeythetestinggoat.com/book/pre-requisite-installations.html for
  why you might not want to use Python 3.7 *for this book*. He also has some
  recomemndations for other Python tutorials at the start of that section.

By the way, we use Django at work, and although many of the details of how we
work are different from the book, it’s *likely* that I might be able to help
if you did work with it and get stuck.

NB: Dive into Python as mentioned at the above link is now at
https://www.diveinto.org/python3/

* https://github.com/CambridgeEngineering/PartIA-Computing-Michaelmas is a
  workbook used for an introduction to Python for Part 1A Engineering students
  at Cambridge University. If you find equations and graph drawing
  comfortable, then this may also be of interest, as an entirely different
  approach. It also uses Jupyter Notebooks, which are worth knowing about.

For interest’s sake, I follow https://www.reddit.com/r/Python/, which
sometimes has interesting things on it. There’s also
https://www.reddit.com/r/learnpython which is specifically aimed at beginner
questions - you’ll have to judge whether the questions and answers there are
also useful. I assume it’s worth a look, though.

Planet Python https://www.planetpython.org/ is an aggregator of Python related
articles - there are often introductions to interesting things referenced
here, so it’s probably worth keeping an eye on (I have it as an RSS feed,
altthough these days the reddit channel has more that’s directly of interest
to me - but your mileage may well vary).

https://stackoverflow.com/ can, as ever, be useful, but be sure that the
answers you’re looking at are for Python 3, and even Python 3.5 or later, or
they’re not so likely to be of use.

Back in the day (picture doddering old man with a stick and a long white
beard) I learnt Python by reading the official tutorial, the reference manual
and the library manual (all at https://www.python.org/doc/). Of course, back
then there weren’t any other alternatives. I’m not 100% convinced the tutorial
is such a good point to start any more, but if your mind is that way inclined
(not everyone is) then the reference manual is interesting, and I definitely
recommend looking at the first few sections of the library reference
https://docs.python.org/3/library/index.html (this will give you the
documentation for the latest version, but you can choose the version you want
with the selector at the top of the page, and it’s normally fairly good at
telling you when something new-ish was introduced in the actual body of the
text).  Hmm - probably Introduction through Built-in Exceptions, and then
string, datetime, collections, pathlib, os.path and os (yes, those are
different - blame history), and then it very much depends on what you want to
do.

If you need to use logging, regular expressions, unicode, argparse (command
line parsing) and a few other things, the HOWTO documents at
https://docs.python.org/3/howto/index.html are actually a better place to
start.

If you’re not wedded to any particular editor, then I generally recommend
either PyCharm or Visual Studio Code as an IDE. I know more about PyCharm, but
MicroSoft have been putting a *lot* of work into their offering as well. If
you’re relatively new to Python, and aren’t a dedicated emacs/vim user, then
an IDE like this can definitely be very helpful. Both have blogs:
https://blog.jetbrains.com/ (covers PyCharm and their other IDEs) and
https://blogs.msdn.microsoft.com/pythonengineering/ respectively. For personal
use, they should both be free.

I hope all of that helps - feel free to come back with more specific
questions/requests if needs be (although I don’t promise to know the answer!)

Notes from the October 2019 CamPUG meeting
==========================================



URLs
====

...


Conferences
===========

See some stuff about going to conferences at `Notes about conferences`_

.. _`Notes about conferences`: conferences.rst

--------

  |cc-attr-sharealike|

  These notes and any related files (i.e., anything in this repository) are
  released under a `Creative Commons Attribution-ShareAlike 4.0 International
  License`_.

.. |cc-attr-sharealike| image:: images/cc-attribution-sharealike-88x31.png
   :alt: CC-Attribution-ShareAlike image

.. _`Creative Commons Attribution-ShareAlike 4.0 International License`: http://creativecommons.org/licenses/by-sa/4.0/
