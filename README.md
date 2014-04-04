Heroku buildpack: poe-ui
===================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [poe-ui](https://github.com/poegroup/poe-ui) apps.
It uses [Make](http://www.gnu.org/software/make/).

Usage
-----

Example usage:

    $ ls
    Makefile  component.json

    $ heroku create --stack cedar --buildpack http://github.com/poegroup/heroku-buildpack-poe-ui.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> poe-ui app detected
    -----> Configuring
    -----> Compiling with Make
