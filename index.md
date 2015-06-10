---
layout: page
title: NGCM Basics Software Prerequisites
subtitle: Installation Instructions
---

# Prerequisites

Prior to the workshop, you should ensure you have the following software installed on your laptop.


## Text Editor
You are free to use your preferred text editor. If you don't have one, we recommend:

### Windows
Notepad++ [https://notepad-plus-plus.org/download/]

### Mac OS X & Linux
Nano, which Terminal based, installed by default). You can verify you have this installed by typing the following at a terminal:

~~~ {.python}
nano
~~~


## Python
We teach with Python 2.7, since it is still the most widely used version. We will also employ the numpy and matplotlib libraries and the nose unit testing framework.

### Mac OS X
Mac OS 10.9 Mavericks and 10.10 Yosemite ship with Python 2.7, numpy and matplotlib installed by default. You will need to install nose. Open a terminal and enter the following command:

~~~ {.python}
sudo easy_install nose
~~~

If you intend to use an earlier version of Mac OS X, please contact us before the event.

### Windows
We recommend the Anaconda Python distribution: [http://continuum.io/downloads]. This provides Python plus the required libraries and frameworks

### Linux
Most distros include Python 2.7 by default. Install the libraries in a terminal like this:

- Ubuntu 14.04LTS and derivatives
  - sudo apt-get install python-numpy
  - python-matplotlib python-nose

- Fedora 22
  - su -
  - dnf install numpy python-matplotlib python-nose


## Git
In this workshop we will work with remote Git repositories hosted at Github. You should create an account there before the event. [https://github.com/join]

### Windows
Download and install Git for Windows [http://git-scm.com/download/win]. You can accept the default installation options. In this workshop we will use Git via the Git Bash command line, installed as part of this package.

### Mac OS X
Git will be installed automatically the first time you try to run it.  Open  terminal and type:

~~~ {.python}
git
~~~

Follow the prompts to install the Apple command line development tools.

### Linux
Install via a terminal like this:

- Ubuntu 14.04LTS and derivatives
  - sudo apt-get install git

- Fedora 22
  - su -
  - dnf install git
  
