Flaskyll - Flask Static Website Generator
==================================

Static website generator using Flask.

# Install

## Create Virtual environment

    $ mkvirtualenv py
    $ workon py

## Instal Pyandoc

Do not use pip version, because it has Pandoc binary path hardcoded in it.

    $ git clone git@github.com:kennethreitz/pyandoc.git
    $ cd pyandoc
    $ python setup.py install

## Clone Flaskyll Repository

    $ git clone https://github.com/aivuk/flaskyll.git

## Install dependencies

    $ cd flaskyll
    $ pip install -r requirements.txt

## Build pages and run

First build the pages to build/ directory:

    $ fab build

Run localserver:

    $ fab run


