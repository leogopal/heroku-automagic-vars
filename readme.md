# Heroku Config Vars Automagic Setter

This python script sets all your heroku config vars directly from a `.env` file automagically.

This script works especially for laravel, but can be used for any other environment, all you just need do is to have a `.env` file, and have your variables set like EXAMPLE_NAME=your_EXAMPLE_name

### Requirements

* python runtime (2.7+) and pip installer (`sudo easy_install pip` on Mac)
* heroku toolbelt (CLI) `brew install heroku/brew/heroku`
* A project already connected to heroku

### Installation

* Add the `heroku-config.py` file to the same location as your `.env` file.

### Usage

- From the cmd, `cd` into the location of your `.env` file locally.
- Run `python heroku-config.py` and you should start seeing your config vars being automagically set.
- Done.
