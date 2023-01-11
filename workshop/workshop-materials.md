---
title: Workshop Materials
nav_title: Materials
---

### Github Repositories

CCDL training materials are available on Github, in either this repository or our shared [training-modules repository](https://github.com/AlexsLemonade/training-modules).

### Slides

PDF versions of the slides we present in this workshop can be found in the [slides directory]({{site.repository_url}}/tree/master/slides) of the `{{site.repository}}` repository, and are also linked to directly from the [schedule](SCHEDULE.md).

### Module Structure

All materials for this workshop can be found in the `training-modules` repository within the [scRNA-seq-advanced](https://github.com/AlexsLemonade/training-modules/tree/{{site.release_tag}}/scRNA-seq-advanced) folder.
This folder includes both instruction notebooks we will walk through during the workshop and exercise notebooks to be used for practice (denoted by the `exercise` prefix).

In this folder, you will notice that there may be two or three versions of some notebook files.
For example, there may be a `02-celltype_assignment-live.Rmd`, a `02-celltype_assignment.Rmd`, and a `02-celltype_assignment.nb.html`.

- The version with `-live.Rmd` at the end is an incomplete version of the notebook, missing some code that will be filled in during the workshop.
- The `.Rmd` file (with no `-live`) is a fully completed version of the notebook, useful for reference in case you might have missed any steps during the workshop.
- The `.nb.html` version of the file is a rendered web page of the notebook.
This file can be downloaded or viewed via the links in the README file that you will see at the bottom of the file listing for each module.

This workshop builds on material found in the [scRNA-seq] folder, which may be a helpful reference.

### RStudio Server

Notebooks and data files required for participation in the workshop will be preloaded for each user on the RStudio server.
