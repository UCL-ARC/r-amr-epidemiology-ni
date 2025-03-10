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

# ![](fig/RStudio_git_diff_icon.png){alt='RStudio screenshot showing the Diff icon in the Git tab of the uppler left panel.'}

In the Git tab of the upper left panel, we can click on the `Diff` icon.
This will show changes made to `index.qmd`

![](fig/RStudio_git_first_diff.png){alt='RStudio screenshot showing changes made to index.qmd and that these are unstaged.'}

Git has noticed that there are changes to `index.qmd`, and that these are currently unstaged.
Currently, Git doesn't know that it needs to keep track of these changes.

To do this, we can check the box in the Staged column for `index.qmd`

# ![](fig/RStudio_git_first_stage.png){alt='RStudio screenshot showing staging of index.qmd and change of ? to A under status column.'}

We can see that under status the orange `?` has changed to a green `A` and in the bottom section the radio button for `Staged` is now selected.

Git now knows that it's supposed to keep track of `index.qmd`,
but it hasn't recorded these changes as a commit yet.

# ![](fig/RStudio_git_first_commit.png){alt='RStudio screenshot showing initial commit message for index.qmd.'}

To get it to do that, we need to type a message in the `Commit message` box and click on `Commit`.

On the completion of the `commit` the following message is displayed in the terminal:
