=========================
Python Learning Resources
=========================

.. contents::

Introduction
============

Occasionally I am asked for advice on how to learn Python, or to get better at
Python programming. I've always felt that I'm not necessarily best placed to
answer this question, as I learnt Python a long time ago [#]_, and there are
many resources available now that were not even thought of then.

Part of the `October 2019`_ CamPUG_ meeting was given over to a discussion of
Python learning resources. This page is meant to fold together my original
notes and the comments and suggestions from that meeting.

I'd love comments / contributions - either via pull requests on this document
on github, by email to me directly (again, via github) or by message via the
CamPUG_ meetup page. Don't worry too much about getting the text formatting
right - I can always fix that.

-- Tibs

.. _`October 2019`: https://www.meetup.com/CamPUG/events/265064979/
.. _CamPUG: https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks

**Note:** Where this page says "I" it means "Tibs", and where it says "we" or
lapses into the passive voice, it may mean information from CamPUG members.

.. [#] in a city far, far away (well, in the early 1990s and in Glasgow, but
       you get the point). There weren't any Python books or other learning
       resources back then, apart from the actual Python documentation itself.

----------------------------

General notes
=============

Whatever you do, make sure you're learning Python 3. Any course that teaches
Python 2 is much too out-of-date.

Many courses out there seem to be teaching with Python 3.6 - that's OK. Later
versions of Python add more nice things, but what you learn with Python 3.6
should continue to be useful.

Do be aware that lots of computers (I'm looking at Mac OS in particular) come
with the ``python`` command set up to run Python 2. So you may need to type
``python3`` to get the right version of Python. Any course you're using should
explain that.

This guide mainly suggests free resources, partly because not everyone has
money to spare for learning Python.

Text that is:

  "indented and in quotes, like this"

is repeating what someone else has said about their resource.

Where to start if you don't have much programming experience
============================================================

Different people learn in different ways, so it's worth having a look at
several of the following.

* `Trinket`_ - an online education framework - code in the browser

  Trinket lets you edit and run Python code in the browser. There are
  currently three Python related tutorials on their front page:

  * `From Blocks to Code`_, which lets you program by assembling blocks into
    programs. This also teaches some basics of Python - in particular, after
    creating the block programs, you can ask it to show you the equivalent
    Python code.

  * `Python with Turtles`_, which uses the Turtle library to draw shapes.

  * `Python for Everybody`_, which is a book to teach the basics of Python3,
    using trinket dialogues for the examples.

  Trinket also provide `Hour of Python`_, which includes the turtles and
  blocks sessions, but also a sequence of challenges and specific tutorials.
  This website also has at least some resources in Spanish, Chinese and Korean.

* scrimba_ - a live programming environment you use while watching videos. The
  front page says

    "Scrimba lets you play around with the instructor's code directly inside
    the screencast. As a result, you'll learn faster and have more fun."

  If you `search for Python`_ then you find quite a few courses,
  many of which look suitable for beginners. There's a mix of free and paid
  courses. Their `Learn Python for free`_ course is, of course, free.

* I recommend the `Django Girls tutorial`_, which starts by teaching what a
  command line is, and works through to creating a web site using Django (and
  boys are allowed to use it, too - it says so in the FAQ). They are also
  creating videos on the "Coding is for Girls" youtube channel, and the
  tutorial pages link to the appropriate video, if it exists.

  You may also find that there is a Django Girls workshop locally, so that you
  can learn in company with others - see https://djangogirls.org/ for more
  information.

* There are a series of resources at `Invent with Python`_, including free
  online books and links to youtube videos and paid courses. If you scroll
  down the page, it gives a brief introduction to each book, and see what
  looks interesting. Good places to start are either "Invent with Python"
  iteself, or "Automate the Boring Stuff with Python". There are also books
  for Lua and Scratch.

* `realpython.com`_ (Real Python Tutorials) provides regular articles and
  videos, aimed at all levels of Python skill, from beginner to advanced. You
  can subscribe to emails, and new posts also appear on `Planet Python`_.  The
  page at https://realpython.com/start-here/ has suggestions about where to
  start depending on you knowledge and needs, including the `Python Basics
  Book`_:

    "Python Basics Is for Complete Beginners to Python and Coding: No Prior
    Programming Experience Necessary."

* If you've got a Raspberry Pi, then there are lots of resources for using
  Python on it. One place to start is `Raspberry Pi Projects`_, or just go to
  https://www.raspberrypi.org/ and start exploring.

* `Pygame Zero`_ teaches you to write sprite games, which happen to use
  Python. It does assume you know some basics.

* If you're the sort of person who takes comfort in equations and graph
  drawing, then you may find the `Part IA Computing (Michaelmas)`_ course
  helpful. This is a Jupyter_ notebook providing a self-study introduction to
  Python for Part 1A Engineering students at Cambridge University. You need to
  a Microsoft Azure account to use the notebooks - this is explained in the
  course notes on the page.

  (Note that that link might be moving by October 2020, as Microsoft appear to
  be making some changes. The source code for that site can be found at
  https://github.com/CambridgeEngineering/PartIA-Computing-Michaelmas, and if
  they do move the notebook site, the github page will probably give a link to
  the new location.)

.. _`Django Girls tutorial`: https://tutorial.djangogirls.org/en/
.. _`Invent with Python`: http://inventwithpython.com/
.. _`Part IA Computing (Michaelmas)`: https://notebooks.azure.com/garth-wells/projects/CUED-IA-Computing-Michaelmas
.. _`realpython.com`: https://realpython.com/
.. _`Learn Python for free`: https://scrimba.com/course/gpython

Finally, don't forget that you can try asking for help on the `CamPUG slack
chat`_. You can join at `this link`_ (and if that doesn't work, there may be
a more up-to-date link in the "What we're about" section at
https://www.meetup.com/CamPUG/). Questions about Python use are probably best
asked in the #python channel on slack.

.. _`CamPUG slack chat`: https://campug.slack.com/
.. _`this link`: https://join.slack.com/t/campug/shared_invite/enQtMzM2NjcwMzM2ODM2LTQyMmQ5MmVlZGMxMzBhOGQ0MTQ1ZGMyMTkzYjc1MWQzM2M2ZDViZDc5NDEyYmViY2QyNWJlMjg2ZTkwNzc3NjM

.. _`PyBites Code Challenges Newbie Bites`: https://codechalleng.es/bites/newbie

Where to start if you already know how to program
=================================================

If you already have some programming skills, then it can actually be a little
bit harder to know what to recommend, because how much one knows can vary so
much, and also because people learn in such different ways.

* First off, it can definitely be worth looking at the resources in the
  previous section, `Where to start if you don't have much programming
  experience`_.

  In particular:

  * the `Django Girls tutorial`_ can be useful for teaching some basic Django
    (you can skim the early parts that you already know)
  * some of the books at `Invent with Python`_ may still be interesting
  * `realpython.com`_ (Real Python Tutorials) really is a good resource for all
    skill levels - Tibs has definitely found some very useful articles from
    there.

* If you enjoy learning by writing games, then PyGame_ provides a framework
  and a lot of resources. There is also `Pygame Zero`_, which provides a
  simpler way of writing games that is easier to get started with.

* I used to recommend Harry Percival's "Test-Driven Development with Python",
  which also available free at `Obey the Testing Goat!`_.  This teaches you
  how to build a Django website (a more complex one than that in the `Django
  Girls tutorial`_) by way of teaching Test Driven Development. As such, it
  does assume some basic Python knowledge, but it also insists that you copy
  out each example (no cut-and-paste), which should help reinforce knowledge.

  The book requires you to use Python 3.6, which is not a big problem, and
  Django 1.11. Unfortunatley Django 1.11 is now getting a bit old, and you
  definitely shouldn't use it for Real Work. It also means that getting all of
  the related software in the correct versions to match may be getting more
  difficult, and having to sort out installation problems when trying to learn
  is not so much fun.

  On the other hand, it's still a good introduction to the concepts of Test
  Driven Development.

.. _`Obey the Testing Goat!`: https://www.obeythetestinggoat.com/
.. _`pre-requisite installations`: https://www.obeythetestinggoat.com/book/pre-requisite-installations.html

Finally, as in the previous section, you can always try asking questions on
the `CamPUG slack chat`_ (join at `this link`_).

Koans
-----

When I was learning Ruby, I found the `Ruby Koans`_ to be very useful. Their
goal is to teach the Ruby language, syntax, structure, and some common
functions and libraries, as well as some of the Ruby culture, and basic
testing.  Other programming languages have adopted this approach (for
instance, see the list at `Learn a new programming language today with
koans`_), and Python is no exception.

One Python example is by Greg Malcolm (but also see the next paragraph), at
https://github.com/gregmalcolm/python_koans. This is partly a port of the
Ruby koans (where approriate) and partly new material.

The koans at https://github.com/arachnegl/python-koans are intended to be done
*before* those by Greg Malcolm, as the author says they are meant to be more
useful to people of a non-programming background.

The koans aren't always easy. Luckily, if you get stuck, or don't understand
the answer, there are normally solutions to be found (via google or duck duck
go or your other favourite search engine). And there are other Python koans as
well - these were just the first ones I found.

.. _`Ruby Koans`: http://www.rubykoans.com/
.. _`Learn a new programming language today with koans`:
   https://www.lauradhamilton.com/learn-a-new-programming-language-today-with-koans

Tools to write your programs with
=================================

Text editors and IDEs
---------------------

You can use any text editor to work with Python, but it's sensible to use
something that at least understands how to indent Python code, and will
preferably help point out mistakes as you make them.

If you're already using a text editor that does this, then it's perfectly
reasonable to carry on with the same editor for Python.


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
known Python IDEs (`Integrated Development Environment`_, an editing
environment specifically tailored to programming), and the ones I tend to
recommend, are:

* VS Code (`Visual Studio Code`_) is a free IDE from Microsoft which
  understands Python and lots of other programming languages. It is also meant
  to be numpy aware.

  There is a blog about Microsoft's Python support at
  https://blogs.msdn.microsoft.com/pythonengineering/

* PyCharm_ from JetBrains.

  The community (free) edition is very good, but if you want to do serious
  Django work then the extra Django support in the paid version is apparently
  worth it.

  The JetBrains blog at https://blog.jetbrains.com/ covers PyCharm and their
  other IDEs.

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

You don't necessarily have to write Python programs in an editor on your own
computer. There are also online editing environments.

* We already mentioned Trinket_ and scrimba_ in `Where to start if you don't
  have much programming experience`_.

* `repl.it`_ gives you an online IDE, including collaborative code editing,
  for a variety of programming languages, including Python.

* Glitch_ is a collaborative programming environment in the browser that makes
  it easy to write web apps in a variety of languages, including Python
  (https://glitch.com/@python)

* Iodide_ lets you create (scientific) notebooks using Python, markdown,
  Javascript and CSS, entering text in one pane in the browser, and seeing the
  result alongside. See `A Brief Tour through Pyodide`_ for more information
  on using it with Python. The project says it is still in alpha, so things
  may change and break.

  (There's obviously some overlap with the capabilities of sites that provide
  live Jupyter notebooks, although the style seems rather different.)

* `Anvil`_ lets you write full stack web apps just using Python. That is, both
  the front end and the back end are both written using Python. There's a
  drag-and-drop interface for designing the front end. The Anvil team come and
  give workshops at CamPUG periodically, and can be found at many Python
  conferences. There are tutorials and documentation at https://anvil.works/learn.

.. _`From Blocks to Code`: https://hourofpython.trinket.io/from-blocks-to-code-with-trinket
.. _`Python with Turtles`: https://hourofpython.trinket.io/a-visual-introduction-to-python
.. _`Python for Everybody`: https://books.trinket.io/pfe/
.. _`Hour of Python`: https://hourofpython.com/
.. _`repl.it`: https://repl.it/
.. _`Glitch`: https://glitch.com
.. _Iodide: https://alpha.iodide.io/
.. _scrimba: https://scrimba.com/
.. _`search for Python`: https://scrimba.com/search?q=python

And also, Jupyter notebooks
---------------------------

Quoting the `Moving on from Mu`_ page, "`Jupyter Notebooks`_ are an amazing way
to create an interactive narrative with code, multi-media and traditional
prose".

Jupyter notebooks can be used as a way of mixing notes (in markdown) and
Python code, with the results of running that code. This idea is very much
based on lab notebooks, where text, calculations and graphs would all be
written down. Only here, the calcualtions and graphs (and other things) can be
generated live from the results of running Python code.

(Also, Python is not the only programming language supported, so this is a
useful technology to use whatever programming language you may be using.)

There is at least one `gallery of interesting Jupyter notebooks`_ out there.

`Try Jupyter`_ lets you try out some tutorial Jupyter notebooks in your
browser. There are tutorials for several programming languages, including Python.

`Microsoft Azure Notebooks`_ provide online Jupyter notebooks, and host
various tutorials presented as Jupyter notebooks (including the Cambridge
Unversity `Part IA Computing (Michaelmas)`_ Python course mentioned
elsewhere). The Azure Notebooks homepage has links to various featured
projects and tutorials, and there is an `informal introduction to Python3`_.

CoCalc_ provides an "online computing environment" that supports a variety of
things, including Python and Jupyter notebooks. They appear to have an
unlimited free trial, which should be enough to experiment.

There are other places on the web where you can store and interact with
Jupyter notebooks - this was just a selection.

.. _Jupyter: https://jupyter.org/
.. _`Jupyter Notebooks`: https://jupyter.org/
.. _`Moving on from Mu`: https://codewith.mu/en/tutorials/1.0/moving-on
.. _`gallery of interesting Jupyter notebooks`:
    https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks
.. _`Try Jupyter`: https://jupyter.org/try
.. _`Microsoft Azure Notebooks`: https://notebooks.azure.com/
.. _`informal introduction to Python3`:
    https://notebooks.azure.com/Microsoft/projects/2018-Intro-Python/html/Introduction%20to%20Python.ipynb
.. _CoCalc: https://cocalc.com/

Puzzles and challenges
======================

Many people need a *purpose* to learn something like Python. For some people
this need for a purpose can be satisfied by programming challenges. For
instance:

* `The Python Challenge`_

  From the About page:
  "Python Challenge is a game in which each level can be solved by a bit of
  (Python) programming. ... All levels can be solved by straightforward and
  very short scripts. ... (well, except of level 32)."

  This expects you to solve problems by writing snippets of Python
  code. Sometimes needs you to think quite hard (to figure out what it wants
  you to do). You're also expected to use some of the standard library, and
  external libraries like the imaging library pillow_ (yes, that's a hint for
  one of the questions).

* `Project Euler`_

  "Project Euler exists to encourage, challenge, and develop the skills and
  enjoyment of anyone with an interest in the fascinating world of
  mathematics".

  This isn't Python specific. It *is* a series of mathematics based problems,
  at many different skill levels, that you can use Python to solve.
  
* `Advent of Code`_

  "Advent of Code is an Advent calendar of small programming puzzles for a
  variety of skill sets and skill levels that can be solved in any programming
  language you like. People use them as a speed contest, interview prep,
  company training, university coursework, practice problems, or to challenge
  each other."

  These come out every December. Again, they're not Python specific, but
  Python works well. Every day from 1st to 25th December, you get a new puzzle
  that builds on the previous one, and the challenge is to sumbit a correct
  solution. The puzzles for previous years (back to 2016) are still there as
  well (click on ``[Events]`` at the top of the `Advent of Code`_ home page),
  so there's a lot to play with here.

* The yearly PyWeek_ challenge:

  1. Invites entrants to write a game in one week from scratch either as an individual or in a team,
  2. Is intended to be challenging and fun,
  3. Will hopefully increase the public body of game tools, code and expertise,
  4. Will let a lot of people actually finish a game, and
  5. May inspire new projects (with ready made teams!)


.. _pillow: https://python-pillow.org/
.. _PyWeek: https://pyweek.org/

Also see the section on `Koans`_.

And if you think you have a decent understanding of Python, take a look at
`What the f*ck Python?`_ which is a page dedicated to "Exploring and
understanding Python through surprising snippets."

.. _`What the f*ck Python?`: https://github.com/satwikkansal/wtfpython


Where to get help and more information
======================================

Places to look for more information
-----------------------------------

Tibs says:

  For interest’s sake, I follow https://www.reddit.com/r/Python/, which
  sometimes has interesting things on it. There’s also
  https://www.reddit.com/r/learnpython which is specifically aimed at beginner
  questions - you’ll have to judge whether the questions and answers there are
  also useful. I assume it’s worth a look, though.

  `Planet Python`_ is an aggregator of Python related articles - there are
  often introductions to interesting things referenced here, so it’s probably
  worth keeping an eye on (I have it as an RSS feed, altthough these days the
  reddit channel has more that’s directly of interest to me - but your mileage
  may well vary).

  https://stackoverflow.com/ can, as ever, be useful, but be sure that the
  answers you’re looking at are for Python 3, and even Python 3.5 or later, or
  they’re not so likely to be of use.

.. _`Planet Python`: https://www.planetpython.org/

Books and documentation
-----------------------
  
* As mentioned in `Where to start if you don't have much programming
  experience`_, `realpython.com`_ has useful articles and videos aimed at all
  levels of knowledge and is worth checking out.
  
* Similarly, the resources at `Invent with Python`_ are worth looking at.

* `Python Idioms (2014)`_ is a set of slides by Safe, one of the original
  CamPUG founders, which gives ten useful Python idioms (commonly used and
  understood ways of doing things)

* `Effective Python`_ (not free) is a book that assumes some knowledge of
  Python, but tries to suggest the way an experienced Python programmer would
  do things (often termed the "Pythonic" way of doing things).
  
* Once you're comfortable with Python, you may be interested in deeper dives
  into how things work. I think "Fluent Python: Clear, Concise, and
  Effective Programming" by Luciano Ramalho (not free: `Fluent Python on amazon.co.uk`_)
  is an excellent book for this purpose.

* And as mentioned before, `What the f*ck Python?`_ challenges the idea that
  one has an understanding of how Python actually works.

The official documentation
--------------------------

Don't forget the official `Python 3 documentation`_ [#]_.

The `Python tutorial`_ is worth re-reading periodically, if only to see what
has become a part of the "basic" language. As it says, it

  "does not attempt to be comprehensive and cover every single feature, or
  even every commonly used feature. Instead, it introduces many of Python’s
  most noteworthy features, and will give you a good idea of the language’s
  flavor and style."

It's probably not ideal as a first place to learn Python from.

Tibs would recommend looking at the first few sections of the `library
reference`_, probably *Introduction* through *Built-in Exceptions*, and then
the chapters on *string*, *datetime*, *collections*, *pathlib*, *os.path* and
*os* (yes, those last three are different - blame history), and then it very
much depends on what you want to do.

.. [#] this will give you the documentation for the latest version. If that's
       not what you want, choose the version you do want with the selector at
       the top of the page. The text itself is normally fairly good at saying
       which version of Python introduced a new-ish feature.

If you need to use *logging*, *regular expressions*, *unicode*, *argparse*
(command line parsing) and a few other things, the HOWTO documents at
https://docs.python.org/3/howto/index.html are actually a better place to
start.

.. _`Python tutorial`: https://docs.python.org/3/tutorial/index.html
.. _`Library reference`: https://docs.python.org/3/library/index.html

Other ideas
-----------

The `Python Tutor - Visualize Python, Java, C, C++, JavaScript, TypeScript,
and Ruby code execution`_ is an interesting page that allows you to type in
Python (or other) code and then see how it executes. I've had someone say it
can be "especially great for learning recursion".
  

Meetings and Conferences
========================

Meetings
--------

One way to learn more is to attend some of the various meetings.

* CamPUG_ itself meets once a month, normally on the first Tuesday of the month.
  We continue to meet virtually

* `Cambridge PyData`_ also meets once a month, normally on the last Wednesday
  of the month. It continues to meet virtually, and (at least sometimes)
  combines its meetings with other PyData meetups.

* Before the pandemic, the `Raspberry Pi Foundation`_ hosted `Raspberry
  Jams`_, sometimes in Cambridge. Hopefully they will resume sometime in the
  future. 

* Also sadly postponed are the International Raspberry Py Robotics
  Competitions, or `Pi Wars`_, which happen in Cambridge over a weekend.

* London has its own `PyData London Meetup`_ and also the `London Python Coding
  Dojo`_ - see their websites for details.

.. _`Cambridge PyData`: https://www.meetup.com/PyData-Cambridge-Meetup
.. _`Raspberry Pi Foundation`: https://www.raspberrypi.org/
.. _`Raspberry Jams`: https://www.raspberrypi.org/jam/
.. _`Pi Wars`: https://piwars.org/
.. _`PyData London Meetup`: https://www.meetup.com/PyData-London-Meetup/
.. _`London Python Coding Dojo`: http://ldnpydojo.org.uk/

One way to keep up with Python events is to subscribe to the UK Python Users
mailing list, at https://mail.python.org/mailman/listinfo/python-uk

Conferences
-----------

* In a more normal year, we would also expect to see the UK Python
  conference. As it says at https://2020.pyconuk.org/, that's sadly not
  happening in 2020.

* Similarly, there was meant to be a Cambridge PyData 2020 conference, which
  has also had to be postponed.

* PyLondinium_ is the London Python conference, and it also postponed the 2020
  event.

* PyCon is the biggest Python conference, normally in the USA. `PyCon 2020`_
  did go ahead, but as a virtual conference, in April 2020.

.. _PyLondinium: https://pylondinium.org/
.. _`PyCon 2020`: https://us.pycon.org/2020/

See some stuff about going to conferences at `Notes about conferences`_

.. _`Notes about conferences`: ./conferences.rst

Videos
------

There are lots of videos out there. In particular, the PyCon and PyCon UK
conferences put a lot of their talks up on YouTube. Have a look at

* The `PyCon UK channel`_ (remember, there is/was no PyCon UK in 2020)
* The `PyLondinium channel`_ (also, didn't happen in 2020, but there are
  videos from 2019 and 2018)
* The `PyCon 2020 channel`_ and the `PyCon 2019 channel`_ (and you can surely
  work out how to find previous years)

Both conferences have talks at all technical levels, as well as talks about
things that aren't directly to do with programming. Lightning talk [#]_
sessions can be especially worth watching.

.. [#] Short talks, of less than 5 minutes, on any topic at all.

.. _`PyCon UK channel`: https://www.youtube.com/channel/UChA9XP_feY1-1oSy2L7acog
.. _`PyLondinium channel`: https://www.youtube.com/channel/UCHh7vOesookNhYvupCCcJxA
.. _`PyCon 2020 channel`: https://www.youtube.com/c/PyCon2020
.. _`PyCon 2019 channel`: https://www.youtube.com/c/PyCon2019

Performance - making Python run faster
======================================

People sometimes ask about how to improve the performance of Python
programs. This depends a bit on what sort of program it is, but here a are a
few hints:

* `High Performance Python`_ by `Ian Ozsvald`_ and Micha Gorelick (also
  available `at amazon`__) is probably the best introduction to this topic.

* Unsurprisingly, the `Cambridge PyData`_ meetup is a good place to ask
  questions about making Python run faster, or finding out better ways to
  approach the sort of problem that makes people ask this question.

* `Software Carpentry`_ and `Data Carpentry`_ are low cost courses for academics

* One of the well known approaches is to use `Cython`_, which gets you closer
  to the performance of C whilst still writing code in something close to Python.

.. _`Ian Ozsvald`: https://ianozsvald.com/
.. _`High Performance Python`: http://shop.oreilly.com/product/0636920028963.do
__ https://www.amazon.co.uk/High-Performance-Python-Performant-Programming/dp/1492055026
.. _`Cython`: https://cython.org/
.. _`Software Carpentry`: https://software-carpentry.org/
.. _`Data Carpentry`: https://datacarpentry.org/


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
     https://www.amazon.co.uk/Fluent-Python-Concise-Effective-Programming/dp/1491946008
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
.. _Pygame: https://www.pygame.org

--------

  |cc-attr-sharealike|

  These notes and any related files (i.e., anything in this repository) are
  released under a `Creative Commons Attribution-ShareAlike 4.0 International
  License`_.

.. |cc-attr-sharealike| image:: images/cc-attribution-sharealike-88x31.png
   :alt: CC-Attribution-ShareAlike image

.. _`Creative Commons Attribution-ShareAlike 4.0 International License`: http://creativecommons.org/licenses/by-sa/4.0/
