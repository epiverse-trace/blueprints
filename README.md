[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![render-blueprints](https://github.com/epiverse-trace/blueprints/actions/workflows/render_blueprints.yml/badge.svg)](https://github.com/epiverse-trace/blueprints/actions/workflows/render_blueprints.yml)
[![DOI](https://zenodo.org/badge/510390227.svg)](https://zenodo.org/badge/latestdoi/510390227)

# Welcome to this repository!

This repository stores the [__Epiverse TRACE Blueprints__](index.qmd) for software development. You can:

* view the blueprints in [quarto / markdown format](index.qmd) on github 

* view the blueprints in [HTML](https://epiverse-trace.github.io/blueprints/)

## Contributions

### Tell us what you think

__Questions__ and __comments__ on the blueprints are welcome through [github issues](https://github.com/epiverse-trace/blueprints/issues). If you would like to suggest edits to the blueprints but do not want to make a _pull request_ (see below), feel free to suggest these edits directly as an issue. 

### Contributions via pull requests

__Contributions__ are welcome via [pull requests](https://github.com/epiverse-trace/blueprints/pulls), usually after discussing edits in an issue. The blueprints file to edit is __index.qmd__. This quarto file is used to render the blueprints to `html`. This rendering is done automatically every time __index.qmd__ changes on the *main* branch. When making pull requests, it is best to only commit changes to the `qmd` file. 

In a nutshell, the workflow for contributions would look something like:

1. [Install quarto](https://quarto.org/docs/get-started/)

2. Clone the repository using SSH; this is only needed the first time your download the git repository.

3. Run `git pull` to fetch the latest version of the repository.

4. Create a new branch to make your changes typing `git checkout -b [name_of_your_branch]`.

5. Make changes to `index.qmd`, save the file.

6. From your terminal, run `quarto render`. The `html` output will be generated in the `_book/` folder.

7. Repeat the two previous steps as many times as needed. Commit the final changes using:

```
git add index.md
git commit -m "quick summary of changes"
git push --set-upstream origin [name_of_your_branch]
```

8. Open a pull request on [github](https://github.com/epiverse-trace/blueprints/pulls), using your branch, and explaining briefly which changes you have made.


### Notes

Please note that this project uses a [Contributor Code of Conduct](https://github.com/epiverse-trace/.github/blob/main/CODE_OF_CONDUCT.md
). By contributing, you agree to abide by its terms.

This work is licensed under a [Creative Commons Attribution 4.0 International License (CC-BY)](https://creativecommons.org/licenses/by/4.0/).
