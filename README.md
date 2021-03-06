# Epydoc

    Copyright (C) Edward Loper
    Author: Edward Loper <edloper@gradient.cis.upenn.edu>
    URL: <http://epydoc.sourceforge.net>
    For license information, see LICENSE.TXT

## Introduction

Epydoc is a tool for generating API documentation for Python
modules, based on their docstrings.  A lightweight markup language
called epytext can be used to format docstrings, and to add
information about specific fields, such as parameters and instance
variables.

## Documentation

Documentation for epydoc, including installation and usage
instructions, and a complete description of the epytext markup
language, is available on the epydoc homepage:

    <http://epydoc.sourceforge.net/>

This documentation is also available in the doc/ subdirectory of
the source distribution.

## Installing

To install epydoc, use make:

    git clone https://github.com/neeraj9/epydoc.git
    cd epydoc/src
    sudo make install
    sudo make installdocs

Or use the distutils setup.py script:

    git clone https://github.com/neeraj9/epydoc.git
    cd epydoc/src
    sudo python setup.py install

## Usage

    Run "epydoc --help" for a description of epydoc's usage.

## Contributing

If you are interested in contributing to epydoc, please email
<edloper@gradient.cis.upenn.edu>.
