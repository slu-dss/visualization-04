# visualization-04 <img src="/img/logo.png" align="right" />
[![](https://img.shields.io/badge/seminar-seminar%20name-brightgreen.svg)](https://github.com/slu-dss/visualization-04/)
[![](https://img.shields.io/badge/lesson%20status-under%20development-red.svg)](https://github.com/slu-dss/visualization-04/)
[![](https://img.shields.io/github/release/slu-dss/visualization-04.svg?label=version)](https://github.com/slu-dss/visualization-04/releases)
[![](https://img.shields.io/github/last-commit/slu-dss/visualization-04.svg)](https://github.com/slu-dss/visualization-04/commits/master)
[![Travis-CI Build Status](https://travis-ci.org/slu-dss/visualization-04.svg?branch=master)](https://travis-ci.org/slu-dss/visualization-04)
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/slu-dss/visualization-04?branch=master&svg=true)](https://ci.appveyor.com/project/slu-dss/visualization-04)

## Lesson Overview
This repository contains the fourth lesson for the Data Visualization in R seminar. This lesson shows us that it is hip to be square when we use geoms.

### Objectives
At the end of this lesson, participants should be able to:

1. Construct scatter plots using the point or jitter geometries
2. Make bar plots via histogram or bar geometries
3. Draw line plots using line or ribbon geometries

### Lesson Resources
* The [`SETUP.md`](/references/SETUP.md) file in the [`references/`](/references) directory contains a list of packages required for this lesson
* The [`notebook/`](/notebook) directory contains...
* The [lesson slides](https://slu-dss.github.io/<repo>/) provide an overview of...
* The [`references/`](/references) directory also contains other notes on changes to the repository, key topics, terms, data sources, and software.

### Extra Resources
* [R for Data Science, Chapter 3 - Data Visualisation](https://r4ds.had.co.nz/data-visualisation.html)
* [R for Data Science, Chapter 28 - Graphics for Communication](https://r4ds.had.co.nz/graphics-for-communication.html)
* [RStudio's `ggplot2` Cheat Sheet](https://www.rstudio.com/resources/cheatsheets/#ggplot2)
* [`ggplot2` extensions gallery](http://www.ggplot2-exts.org/gallery/)

## Lesson Quick Start
### Install Software
The packages we'll need for today can be installed using:

```r
install.packages(c("tidyverse", "here", "knitr", "rmarkdown", "usethis", "forecast"))
```

## Access Lesson
You can download this lesson to your Desktop easily using `usethis`:

```r
usethis::use_course("https://github.com/slu-dss/visualization-04/archive/master.zip")
```

By using `usethis::use_course`, all of the lesson materials will be downloaded to your computer, automatically extracted, and saved to your desktop. You can then open the `.Rproj` file to get started.

## Contributor Code of Conduct
Please note that this project is released with a [Contributor Code of Conduct](.github/CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms.

## About the SLU DSS
### Reproducible Research in R

### About the SLU Data Science Seminar
The [SLU Data Science Seminar](https://slu-dss.githb.io) (DSS) is a collaborative, interdisciplinary group at Saint Louis University focused on building researchers’ data science skills using open source software. We currently host seminars focused on the programming language R. The SLU DSS is co-organized by [Christina Gacia, Ph.D.](mailto:christina.garcia@slu.edu), [Kelly Lovejoy, Ph.D.](mailto:kelly.lovejoy@slu.edu), and [Christopher Prener, Ph.D.](mailto:chris.prener@slu.edu}). You can keep up with us here on GitHub, on our [website](https://slu-dss.githb.io), and on [Twitter](https://twitter.com/SLUDSS).

### About Saint Louis University <img src="/img/sluLogo.png" align="right" />
Founded in 1818, [Saint Louis University](http://www.slu.edu) is one of the nation’s oldest and most prestigious Catholic institutions. Rooted in Jesuit values and its pioneering history as the first university west of the Mississippi River, SLU offers nearly 13,000 students a rigorous, transformative education of the whole person. At the core of the University’s diverse community of scholars is SLU’s service-focused mission, which challenges and prepares students to make the world a better, more just place.
