Code Review Field Test
================

## Objectives

- test the usability of a code review process built on git and github
- get participants in this exercise technologically set up to
  participate in a code review

## Setting up

- [R](https://www.r-project.org/)
- [RStudio](https://www.rstudio.com/products/rstudio/download/)
- [git](https://git-scm.com/download/win)
- [github](https://github.com/) (create an account, or log in)

## Instructions

1.  Open RStudio
2.  Navigate to ‘Terminal’
3.  Clone the repository `context-dependent/code-review-exercise`
4.  Open the repository as a project
5.  In the terminal again, create and checkout a branch
6.  Add the function `hello_<yourname>()` to R/change_me.R
7.  Add, commit, and push the changes to your branch
8.  navigate to the remote repository in a browser, and create a ‘pull
    request’
9.  observe comments from reviewer


## Key Commands

```
# 2 clone

> git clone https://github.com/<repo-owner>/<repo-name>

# 5 branch

> git checkout -b <your-branch-name>

# 7 add, commit, push

> git add -A
> git commit -m "<an informative message>?
> git push -u origin <your-branch-name>
```