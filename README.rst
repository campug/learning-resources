=========================
Python Learning Resources
=========================

.. contents::

Introduction
============

Occasionally I am asked for advice on how to learn Python, or to get better at
Python programming. I've always felt that I'm not necessarily best placed to
answer this question, as I learnt Python a long time ago, and there are many
resources available now that were not even thought of then.

Part of the `October 2019`_ CamPUG_ meeting was given over to a discussion of
Python learning resources. This page is meant to fold together my original
notes and the comments and suggestions from that meeting.

-- Tibs

.. _`October 2019`: https://www.meetup.com/CamPUG/events/265064979/
.. _CamPUG: https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks

**Note:** Where this page says "I" it means "Tibs", and where it says "we" or
lapses into the passive voice, it may mean information from CamPUG members.

----------------------------

Tibs' original notes
====================

**This is a form of the text that Tibs has been using when asked how to learn
Python.** NB: bits of this are gradually being moved into the rest of the text.

Whilst I’m not sure how useful I can be with recomendations on learning
Python, since (a) I did it myself so long ago and since then have “grown with
it”, and (b) I’m not quite sure what your starting position is, I can
definitely try to give some pointers.

As places to start, I often recommend:

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

----------------------------

Tools to write your programs with
=================================

Text editors and IDEs
---------------------

You can use any text editor to work with Python, but it's better to use
something that at least understands how to indent Python code, and will
preferably help point out mistakes as you make them.

If you're already using a text editor that does this, then it's perfectly
reasonable to carry on with the same editor for Python. However, you may also
want to explore an IDE (`Integrated Development Environment`_), an editing
environment specifically tailored to programming.

If you're new to programming, then I recommend the Mu_ editor.  Mu is a Python
code editor for beginner programmers based on extensive feedback given by
teachers and learners. As such, its core beliefs are:

  - Less is More: Mu has only the most essential features, so users are not
    intimidated by a baffling interface.
  - Tread the Path of Least Resistance: Whatever the task, there is always
    only one obvious way to do it with Mu.
  - Keep it Simple: It's quick and easy to learn Mu ~ complexity impedes a
    novice programmer's first steps.
  - Have fun! Learning should inspire fun ~ Mu helps learners quickly create
    and test working code.

It also makes it very easy to send Python programs to things like the BBC
`micro:bit`_ and Adafruit_ boards that run CircuitPython_

.. _`micro:bit`: http://microbit.org/
.. _Adafruit: https://adafruit.com/
.. _CircuitPython: https://learn.adafruit.com/welcome-to-circuitpython/overview

There are tutorials for how to use Mu at https://codewith.mu/en/tutorials/.

I recommend Mu for pair programming at CamPUG, as it saves discussion of
what editor to use, and concentrates the mind on programming rather than
clever editor tricks.

If you're wanting something more sophisticated than Mu, then the two best
known Python IDEs, and the ones I tend to recommend, are:

* VS Code (`Visual Studio Code`_) from Microsoft.
  - which is apparently beginning to be numpy
  aware. <ref their blog as well>
* PyCharm_ - the community edition is very good, but if you want to do serious

Both have blogs: https://blog.jetbrains.com/ (covers PyCharm and their other
IDEs) and https://blogs.msdn.microsoft.com/pythonengineering/
respectively. For personal use, they should both be free.

Note:

* VS Code is apparently beginning to know about how numpy works.
* The community (free) edition of PyCharm is very good, but apparently if you
  want to do serious Django work then the extra Django support in the paid
  version is apparently worth it.

.. _`Integrated Development Environment`: https://en.wikipedia.org/wiki/Integrated_development_environment
.. _PyCharm: https://www.jetbrains.com/pycharm/
.. _Spyder: https://www.spyder-ide.org/
.. _anaconda: https://www.anaconda.com/distribution/

At the October 2019 CamPUG meeting on learning resources, mention was also
made of Spyder_, which is distributed as part of the Anaconda_ Python
distribution. This is an IDE aimed at scientific users.

There is also Atom_, which is a free editor developed by GitHub. This is a
more general text editor that has optional support for many programming
languages, including Python.


Online coding environments
--------------------------

* `Trinket`_ - an online education framework - code in the browser
* https://repl.it/ - a bit more advanced
* https://glitch.com/@python - Python at https://glitch.com/. Collaborative
  coding.
* https://alpha.iodide.io - `A Brief Tour through Pyodide`_
* `Anvil`_
* scrimba - a live programming environment you use while watching videos

And also
--------

Quoting the `Moving on from Mu`_ page, `Jupyter Notebooks`_ are an amazing way
to create an interactive narrative with code, multi-media and traditional
prose.

Jupyter notebooks can be used as a way of mixing notes (in markdown) and
Pythod code, with the results of running that code. This idea is very much
based on lab notebooks, where text, calculations and graphs would all be
written down. Only here, the calcualtions and graphs (and other things) can be
generated live from the results of running Python code.

(Also, Python is not the only programming language supported, so this is a
useful technology to use whatever programming language you may be using.)

There is at least one `gallery of interesting Jupyter notebooks`_ out there.

.. _`Jupyter Notebooks`: https://jupyter.org/
.. _`Moving on from Mu`: https://codewith.mu/en/tutorials/1.0/moving-on
.. _`gallery of interesting Jupyter notebooks`:
    https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks

Notes from the October 2019 CamPUG meeting
==========================================

This started as a transcription of the notes I took at the aforesaid meeting,
so I can fold them into some sensible text.




* `Pygame Zero`_, and the yearly PyGame competition

* "Everything you want to know about functions" (talk at PyCon UK)

* github | satwikkansal | wtfpython
  
**Maybe have sections for:**

Puzzles and challenges
----------------------

Ben, like many of us, needs a *purpose* to learn something like Python. He
finds programming challenges very useful - for instance:

* `The Python Challenge`_
* `Project Euler`_ - not Python specific, mathematics based, problems at many
  different skill levels
* `Advent of Code`_ - every December. Again, not Python specific

Other ideas:

* The yearly PyWeek_ challenge:

  1. Invites entrants to write a game in one week from scratch either as an individual or in a team,
  2. Is intended to be challenging and fun,
  3. Will hopefully increase the public body of game tools, code and expertise,
  4. Will let a lot of people actually finish a game, and
  5. May inspire new projects (with ready made teams!)

.. _PyWeek: https://pyweek.org/

`Koans`_ below


Information sources
-------------------
- online
- books

Online resources and books:
  
* realpython.com - videos, beginner up to advanced, and there's a good book,
  the `Python Basics Book`_. I've definitely found some very useful articles
  from this resource.
* Automate the Hard Things - I've heard good things about this as a way into
  Python
* "Fluent Python: Clear, Concise, and Effective Programming" by Luciano
  Ramalho - several of us think this is more a second book, for reading
  once you're fairly fluent, but it is invaluable if you like deep dives into
  how things work and why, and how to use them. `Fluent Python on amazon.co.uk`_
* `Effective Python`_
* `Python Idioms (2014)`_ - by Safe, one of the original CamPUG founders

Other ideas:

* `Python Tutor - Visualize Python, Java, C, C++, JavaScript, TypeScript, and Ruby code execution`_
   "especially great for learning recursion"

* `Grok Learning | Learn to code from your browser`_

* The Raspberry Py Foundation:
  `Online courses from Raspberry Pi Foundation`_ and
  `Raspberry Pi Projects`_

* futurelearn.com

* `PyBites`_ - for instance, `PyBites – Code Challenge 63 - Automatically
  Generate Blog Featured Images`_
  
Online coding courses
---------------------


Meetings
--------

CamPUG itself.

Cambridge PyData meetup, last Wednesday of the month, same venue as CamPUG.

Raspberry Pi Foundation: Raspberry Jams

PiWars meetings at makespace.

London PyData.

The London Python Code Dojo.

Courses
-------


Other ideas
-----------

* volunteering on StackOverflow

Someone asked about how to improve the performance of Python programs. This
depends a bit on what sort of program it is, but answers included:

* Ian Ozsvald and Micha Gorelick, `High Performance Python`_ (also available
  `at amazon`__, and `there's a new edition coming out in July 2020`__)

* Software Carpentry and Data Carpentry are low cost courses for academics

* One of the well known approaches is to use `Cython`_, which gets you closer
  to the performance of C whilst still writing code in something close to Python.

.. _`High Performance Python`: http://shop.oreilly.com/product/0636920028963.do
__ https://www.amazon.co.uk/High-Performance-Python-Performant-Programming/dp/1449361595
__ https://www.amazon.co.uk/High-Performance-Python-Performant-Programming/dp/1492055026
.. _`Cython`: https://cython.org/

URLs
====

These are the tabs that were opened on my laptop during the October 2019
Campug Meeting (thanks, Ben, for thinking to do that - it never occurred to
me!) that have not yet been incorporated into the text above:

* `Python 3 Documentation`_
* `Python 101: Sets - Scrimba Tutorial`_
* `regex - Adding double quotes to string is giving me incorrect data in Python - Stack Overflow`_
* `The Ultimate Code Kata`_

.. _`The Python Challenge`: http://www.pythonchallenge.com/
.. _`Trinket`: https://trinket.io/
.. _`Project Euler`: https://projecteuler.net/
.. _`Advent of Code`: https://adventofcode.com/
.. _`Python 3 Documentation`: https://docs.python.org/3/
.. _`Visual Studio Code`: https://code.visualstudio.com/
.. _`Atom`: https://atom.io/
.. _`Project Jupyter`: https://jupyter.org/
.. _Mu: https://codewith.mu/
.. _`Python Basics Book`: https://realpython.com/products/python-basics-book/
.. _`Anvil`: https://anvil.works/
.. _`A Brief Tour through Pyodide`: https://alpha.iodide.io/notebooks/300/
.. _`Fluent Python on amazon.co.uk`:
     https://www.amazon.com/Fluent-Python-Concise-Effective-Programming/dp/1491946008
.. _`Effective Python`: https://effectivepython.com/
.. _`python idioms (2014)`: http://safehammad.com/downloads/python-idioms-2014-01-16.pdf
.. _`Python 101: Sets - Scrimba Tutorial`: https://scrimba.com/p/pRB9Hw/cWQweVT2
.. _`Online courses from Raspberry Pi Foundation`: https://www.futurelearn.com/partners/raspberry-pi
.. _`regex - Adding double quotes to string is giving me incorrect data in Python - Stack Overflow`: https://stackoverflow.com/questions/58191318/adding-double-quotes-to-string-is-giving-me-incorrect-data-in-python
.. _`Python Tutor - Visualize Python, Java, C, C++, JavaScript, TypeScript, and Ruby code execution`: http://pythontutor.com/
.. _`Grok Learning | Learn to code from your browser`: https://groklearning.com/
.. _`Raspberry Pi Projects`: https://projects.raspberrypi.org/en/
.. _`PyBites`: https://pybit.es/
.. _`PyBites – Code Challenge 63 - Automatically Generate Blog Featured Images`: https://pybit.es/codechallenge63.html
.. _`The Ultimate Code Kata`: https://blog.codinghorror.com/the-ultimate-code-kata/
.. _`Pygame Zero`: https://pygame-zero.readthedocs.io/en/stable/

Koans
=====
Probably fold into the section on puzzles?

When I was learning Ruby, I found the `Ruby Koans`_ to be very useful. Their
goal is to teach the Ruby language, syntax, structure, and some common
functions and libraries, as well as some of the Ruby culture, and basic
testing.

Other programming languages have adopted this approach (for instance, see the
list at `Learn a new programming language today with koans`_), and Python is
no exception.

One Python example is at https://github.com/gregmalcolm/python_koans - this is
partly a port of the Ruby koans (where approriate) and partly new material.

The koans at https://github.com/arachnegl/python-koans are intended to be done
*before* those by Greg Malcolm, as the author says they are meant to be more
useful to people of a non-programming background.

Note that one can quite often find *solutions* to the koans as well, if you
really get stuck. And there are other Python koans as well - these were just
the first ones I found.

.. _`Ruby Koans`: http://www.rubykoans.com/
.. _`Learn a new programming language today with koans`:
   https://www.lauradhamilton.com/learn-a-new-programming-language-today-with-koans

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
