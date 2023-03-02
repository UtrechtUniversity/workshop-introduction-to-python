---
title: Setup
---

## Overview

The course materials are designed to be run on a personal computer.
All of the software and data used are freely available online,
and instructions on how to obtain them are provided below.

If you have any questions, or are not comfortable with doing the installation yourself
join the [RDM walk-in hours][walk-in-hours] to ask for help.

## Install Python

In this course, we will be using Python 3 with some of its most popular scientific libraries.
Although one can install a plain-vanilla Python and all required libraries by hand,
we recommend installing [Anaconda][anaconda-website],
a Python distribution that comes with everything we need for the lesson. 
Detailed installation instructions can be found in the [Anaconda documentation][anaconda-install],
or by following the instructions below.

{% include python.html %}

## Obtain lesson materials

1. Download [??-data.zip][zipfile-data]
        and [??-code.zip][zipfile-code].
2. Create a folder called `intro-python` on your Desktop.
3. Move downloaded files to `intro-python`.
4. Unzip the files.

You should see two folders called `data` and `code` in the `intro-python` directory on your
Desktop.

## Launch Python interface

To start working with Python, we need to launch a program that will interpret and execute our
Python commands. Below we list several options. If you don't have a preference, proceed with the
top option in the list that is available on your machine. Otherwise, you may use any interface
you like.

## Option A: Jupyter Notebook

A Jupyter Notebook provides a browser-based interface for working with Python.
If you installed Anaconda, you can launch a notebook in two ways:

> ## Anaconda Navigator
>
> 1. Launch Anaconda Navigator.
> It might ask you if you'd like to send anonymized usage information to Anaconda developers.
> Make your choice and click "Ok, and don't show again" button.
> 2. Find the "Notebook" tab and click on the "Launch" button.
> Anaconda will open a new browser window or tab with a Notebook Dashboard showing you the
> contents of your Home (or User) folder.
> 3. Navigate to the `data` directory by clicking on the directory names leading to it.
> `Desktop`, `intro-python`, then `data`:
> 4. Launch the notebook by clicking on the "New" button and then selecting "Python 3".
{: .solution}

> ## Command line (Terminal)
>
> 1\. Navigate to the `data` directory:
>
> > ## Unix shell
> > If you're using a Unix shell application, such as Terminal app in macOS, Console or Terminal
> > in Linux, or [Git Bash][gitbash] on Windows, execute the following command:
> > ~~~
> > cd ~/Desktop/intro-python/data
> > ~~~
> > {: .language-bash}
> {: .solution}
>
> > ## Command Prompt (Windows)
> > On Windows, you can use its native Command Prompt program.  The easiest way to start it up is
> > pressing <kbd>Windows Logo Key</kbd>+<kbd>R</kbd>, entering `cmd`, and hitting
> > <kbd>Return</kbd>. In the Command Prompt, use the following command to navigate to
> > the `data` folder:
> > ~~~
> > cd /D %userprofile%\Desktop\intro-python\data
> > ~~~
> > {: .source}
> {: .solution}
>
> 2\. Start Jupyter server
>
> > ## Unix shell
> > ~~~
> > jupyter notebook
> > ~~~
> > {: .language-bash}
> {: .solution}
>
> > ## Command Prompt (Windows)
> > ~~~
> > python -m notebook
> > ~~~
> > {: .source}
> {: .solution}
>
> 3\. Launch the notebook by clicking on the "New" button on the right and selecting "Python 3"
> from the drop-down menu.
{: .solution}

&nbsp; <!-- vertical spacer -->

## Option B: IPython interpreter

IPython is an alternative solution situated somewhere in between the plain-vanilla Python
interpreter and Jupyter Notebook. It provides an interactive command-line based interpreter with
various convenience features and commands. You should have IPython on your system if you installed
[Anaconda][anaconda-website].

To start using IPython, execute:
~~~
ipython
~~~
{: .source}

&nbsp; <!-- vertical spacer -->

## Option C: plain-vanilla Python interpreter

To launch a plain-vanilla Python interpreter, execute:
~~~
python
~~~
{: .source}

If you are using [Git Bash on Windows][gitbash], you have to call Python _via_ `winpty`:
~~~
winpty python
~~~
{: .source}


The instructions on this page were adapted from the [setup instructions of the Software Carpentries "Programming with Python" course][swcarpentry-python] and [their Workshop Template Python installation instructions][carpentries-template], both released under the [Creative Commons Attribution license][license]. Changes to the material were made, and can be tracked in the Git repository associated with this course.

[anaconda-install]: https://docs.anaconda.com/anaconda/install
[anaconda-website]: https://www.anaconda.com/
[carpentries-template]: https://carpentries.github.io/workshop-template/#python
[gitbash]: https://gitforwindows.org
[license]: https://creativecommons.org/licenses/by/4.0/
[swcarpentry-python]: https://swcarpentry.github.io/python-novice-inflammation/setup.html
[walk-in-hours]: https://www.uu.nl/en/research/research-data-management/walk-in-hours-workshops/walk-in-hours-research-data-software
[zipfile-code]: #
[zipfile-data]: #
