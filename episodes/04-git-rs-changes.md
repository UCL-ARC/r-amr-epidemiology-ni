---
title: Tracking Changes
teaching: 20
exercises: 0
---

::::::::::::::::::::::::::::::::::::::: objectives

- Go through the modify-add-commit cycle for one or more files.
- Explain where information is stored at each stage of that cycle.
- Distinguish between descriptive and non-descriptive commit messages.

::::::::::::::::::::::::::::::::::::::::::::::::::

:::::::::::::::::::::::::::::::::::::::: questions

- How do I record changes in Git?
- How do I check the status of my version control repository?
- How do I record notes about what changes I made and why?

::::::::::::::::::::::::::::::::::::::::::::::::::

We will be working on our `amr-data-dictionary`project and should be in the `amr-data-dictionary` directory.

![](fig/RStudio_screenshot_files.png){alt='RStudio screenshot showing the current working directory in the Files tab}

We will be editing the file `index.qmd`.

![](fig/RStudio_index_qmd_start.png){alt='RStudio screenshot showing the default content of index.qmd automatically created.'}

We will start by replacing the initial line of text: `This is a Quarto website.`

With the following text:

```output
## About

This web page will provide metadata information about the data files used 
for the course Introduction to R, databases and reproducibility for AMR epidemiologists.

```
Save your changes to the file.

