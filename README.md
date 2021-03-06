
<!-- README.md is generated from README.Rmd. Please edit that file -->
[![Licence](https://img.shields.io/github/license/mashape/apistatus.svg)](http://choosealicense.com/licenses/mit/) ![Project Status: WIP – Initial development is in progress, but there has not yet been a stable, usable release suitable for the public.](http://www.repostatus.org/badges/latest/wip.svg)\](<http://www.repostatus.org/#wip>)

Roel's Personal Templates package
=================================

This is a nice and opinionated package with templates, primarily for personal use. I use these templates to make sure I keep to best practices, and frankly to just help remind me of stuff I tend to forget.

Current status of project
=========================

Some of the templates are for other projects, mostly online, and some are more specific for R-packages.

#### Non-packages

-   \[\] rscripts (using date, names and stuff)
-   \[\] rmarkdown for blogdown post
-   \[\] travis file for non-package

#### Specifically for packages

-   \[\] rmarkdown readme for packages
-   \[\] markdown readme for packages (if there is no need for rmd file)
-   \[\] standard .gitignore file
-   \[\] travis file that also lints and codecov
-   \[\] standard vignette
-   \[\] changelog

Example usage
-------------

`template::rscript()`

Installation instructions
-------------------------

*Really, you should probably not install this on your computer if you are not me. But you could fork and modify it as [![fork this repo](http://githubbadges.com/fork.svg?user=RMHogervorst&repo=templates&style=flat&color=lightgrey&background=4c1)](https://github.com/RMHogervorst/templates/fork) have done.* Install the package using devtools. `devtools::install_github("rmhogervorst/template")` templates is already a seperate repo... Confusing right?

*Yes I realise I am not using the best practices here*
