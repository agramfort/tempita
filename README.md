Tempita
-------

A small templating language for text substitution, originally
authored by [Ian Bicking](https://bitbucket.org/ianb).

It isn't intended to be the Next Big Thing in templating, just a
handy little templating language for when a project outgrows
string.Template or {} substitution.

It's small, it embeds Python in strings, and it doesn't do much else.

You can read about the language, the interface and that's it, there's
nothing more to learn about it.

You can install the original 0.5 from the
[bitbucket repository](https://bitbucket.org/ianb/tempita) with:

    easy_install Tempita==dev

Note from gjhiggins
-------------------

I transmigrated this to GitHub in order to take advantage of travis-ci
continuous integration and took the opportunity to give the py3 compat
and tests a buffing (March 2013).

[![Build Status](https://travis-ci.org/gjhiggins/tempita.png?branch=master)](https://travis-ci.org/gjhiggins/tempita)