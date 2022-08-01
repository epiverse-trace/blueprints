[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![render-blueprints](https://github.com/epiverse-trace/blueprints/actions/workflows/render_blueprints.yml/badge.svg)](https://github.com/epiverse-trace/blueprints/actions/workflows/render_blueprints.yml)

# Welcome to this repository!

This repository stores the [__software development blueprints__](https://github.com/epiverse-trace/blueprints/blob/main/blueprints.md) for _Epiverse-TRACE_. You can:

* view the blueprints in [markdown format](https://github.com/epiverse-trace/blueprints/blob/main/blueprints.md) on github 

* download them in [pdf format](https://github.com/epiverse-trace/blueprints/raw/main/blueprints.pdf)

* download them in <a href="https://github.com/epiverse-trace/blueprints/raw/main/blueprints.html" download="epiverse_trace_blueprints.html">html format</a> 

Note: github may show you the html source instead of downloading the file; if
that happens, right click on the newly opened page and save the file as
'blueprints.html' (or any name of your choosing).




## Contributions

### Tell us what you think

__Questions__ and __comments__ on the blueprints are welcome through [github issues](https://github.com/epiverse-trace/blueprints/issues). If you would like to suggest edits to the blueprints but do not want to make a _pull request_ (see below), feel free to suggest these edits directly as an issue. 


### Contributions via pull requests

__Contributions__ are welcome via [pull requests](https://github.com/epiverse-trace/blueprints/pulls), usually after discussing edits in an issue. The blueprints file to edit is __blueprints.Rmd__ (not *blueprints.md*). This Rmarkdown file is used to render the blueprints to different formats: `md`, `pdf`, and `html`. This rendering is done automatically every time __blueprints.Rmd__ changes on the *main* branch. When making pull requests, it is best to only commit changes to the `Rmd` file. 

In a nutshell, the workflow for contributions would look something like:

1. Clone the repository using SSH (note: all _Epiverse-TRACE_ repos require [2FA](https://docs.github.com/en/authentication/securing-your-account-with-two-factor-authentication-2fa/configuring-two-factor-authentication)); this is only needed the first time your download the git repository.

2. Run `git pull` to fetch the latest version of the repository.

3. Create a new branch to make your changes typing `git checkout -b [name_of_your_branch]`.

3. Make changes to `blueprints.Rmd`, save the file.

4. From R, run `rmarkdown::render("blueprints.Rmd", output_format = "all")` to check your changes locally on the `pdf`, and `html` outputs.

5. Repeat steps 3 and 4 as many times as needed. Commit the final changes using:
```
git add blueprints.Rmd
git commit -m "quick summary of changes"
git push --set-upstream origin [name_of_your_branch]
```

6. Open a pull request on [github](https://github.com/epiverse-trace/blueprints/pulls), using your branch, and explaining briefly which changes you have made.


### Notes

Please note that this project uses a [Contributor Code of Conduct](https://github.com/epiverse-trace/linelist/blob/main/CODE_OF_CONDUCT.md
). By contributing, you agree to abide by its terms.

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC-BY)](https://creativecommons.org/licenses/by/4.0/).
