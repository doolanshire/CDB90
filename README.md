# CDB90

This repository contains [professor Jeffrey Arnold's version](https://github.com/jrnold/CDB90) of the CDB90 Land Battle Database in CSV format, along with the original dataset created in the 1984 USACAA study *Analysis of Factors That Have Influenced Outcomes of Battles and Wars: A Data Base of Battles and Engagements*, also as offered by him.

I have compiled the CSV files into a single SQLite database for ease of use, and gathered the PDF scans for all six volumes of the original USACAA study.

## Purpose

The aim of this personal project is the analysis and future expansion of the database for historical research. Additionally, it is intended to keep and offer the data from CDB90 in a format that is easy and convenient to use, should anyone require it.

## Files

* **data**: directory containing the CSV files, as cleaned up by jrnold.
* **src-data**: the original dataset also as presented by jrnold.
* **CDB90.db**: a unified SQLite database compiled by me from the CSV files, with the correct data type affinities assigned for each column. Keep in mind that in SQLite datetime is stored as string, and boolean as integer (0, 1).
* **originalpub**: the scanned PDF files for all six volumes of the USACAA study, describing the database and the conclusions of the initial analysis.

## To do

* Write a more complete documentation
* Code scripts to query and plot that database.

## License

The data in the *data* and *src-data* directories is released under the [odc-by](https://opendatacommons.org/licenses/by/) license as in the original release by [jrnold](https://github.com/jrnold/CDB90).

The SQLite database made by the author of this repository is similarly released under the [odc-by](https://opendatacommons.org/licenses/by/) license.

Any programs and scripts are [MIT license](https://opensource.org/licenses/MIT) unless stated otherwise.
