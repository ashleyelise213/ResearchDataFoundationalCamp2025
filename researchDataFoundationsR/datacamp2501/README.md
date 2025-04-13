Author: Ellery Galvin, PhD student and Statistics Specialist to the CRDDS
Org: Center for Research Data and Digital Scholarship
Contact: ellery.galvin@colorado.edu
Website: https://cu-boulder-crdds.github.io/Research-Data-Foundations-Camp-2025-January/content/data-analysis-in-R.html


## Purpose
This folder contains materials for the Research Data Foundations Camp held in Jan, 2025.  It has been distributed to all the participants.

## Contents

- `data`  contains files to be read in by R
    - `ClimateAndArt.csv` is an export of publication metadata from the Web of Science.
    - `iris.csv` is data concerning the anatomy of irises collected in Anderson, 1936; Fisher, 1936.
    - `working.directory.txt` contains text about how to use working directories, written by the author.
- `export` contains files saved from within `notes.qmd` via R commands.
- `html` contains files need to serve `notes.html` in a browser.  It was exported by Quarto
- `notes_cache` contains intermediate results for code cells in `notes.qmd` stored from previous runs.  Quarto uses the cache to render `notes.qmd` cells when the cell has not changed.
- `notes_files` contains images needed in the `html`
- `solutions` contains a limited set of solutions to exercises that are required to proceed to subsequent code chunks in `notes.qmd`.
- `setup.R` has a list of packages needed for the code in `notes.qmd`.  It should be run once after R has been installed and VS Code configured.


