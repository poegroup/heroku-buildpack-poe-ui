Heroku buildpack: simple-stack-ui
===================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) for [simple-stack-ui](https://github.com/CamShaft/simple-stack-ui) apps.
It uses [Make](http://www.gnu.org/software/make/).

Usage
-----

Example usage:

    $ ls
    Makefile  component.json

    $ heroku create --stack cedar --buildpack http://github.com/CamShaft/heroku-buildpack-simple-stack-ui.git

    $ git push heroku master
    ...
    -----> Heroku receiving push
    -----> Fetching custom buildpack
    -----> simple-stack-ui app detected
    -----> Configuring
    -----> Compiling with Make
