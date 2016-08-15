# OpenHours
## http://openhours.io
### Public, Open Source Project Effort Tracker.

Open Hours is a small project designed to answer the question:

**"What is the effort cost of maintaining all of this open source software?"**

It does this by maintaining a public database of hours that OSS maintainers have
spent on their projects on a weekly basis (and some cool reports of this data
sliced in various intesteresting ways).

Ultimately we're looking to get some solid data that can be used as a first step
in solving the problem of OSS Contributor and Maintainer burnout, and Securing
the Open Source Supply Chain (See below for further discussion on the topics).

This repo is the actual webapp, written in python that sits up at openhours.io
and manages the data. Its a super simple Pyramid / SQL Alchemy app designed to
be hosted and deployed on Heroku. It also uses GitHub to auth maintainers.

Feel free to PR or ticket your bugs, fixes and other funky things. Its super
hastily put together but isn't doing anything too amazing so should be stable
enough for our purposes.

## Resources

Below are a list of links that include discussions about the problem or realting
to it, as well as other source material.

* ["Paying the Piper" ticket "What is the cost" -- part of the PyBees project](https://github.com/pybee/paying-the-piper/issues/75#issuecomment-239724072)
* PyConAU 2016 Sunday Keynote -- The original inspiration

## Contributors

* Ash Guy <ash@ashguy.com> (Maintainer... heh.)

