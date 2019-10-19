# SASTRA Deemed University Seminar Report

Compiler user: XeLaTeX

## Files
* `samplereport.tex` - The file that generates the PDF
* `projectreportcommands.sty` - The package that provides commands for report
* `seminarreport.cls` - The definition of the document class
* `sample.bib` - The file that holds bibliography information

### The Document Class - `seminarreport`
This file defines how the document is structured. This includes Margins, Fonts, styles for Table of Contents, References, etc.

Using this as the document class makes sure your document looks right.

### The Commands
Most of the commands used here are defined in the file `projectreportcommands.sty`.

* `\defstudentname` - This command is used to set the student's name
* `\defstudentregno` - This command is used to set the student's reg no.
* `\defhisher`  - Sets the pronoun to use: his/her
* `\defsemester` - Sets the semester for the report
* `\defstudyyear` - Sets the current year of study. `~` is used for non breaking space
* `\defguide` - Sets the name of the guide
* `\title` - Sets the title of your work
* `\makeseminarfirstpage` - Generates the first page for your report
* `\makeseminarsecondpage` - Generates the second page for the report
* `\bonafide` - Generates the bonafide certificate for your work
* `\acknowledgement` - Creates the acknowledgement page with the content you pass as argument.
* `\fakesection` - Creates an entry in the Table of contents

### Built in Commands of Latex
* `\tableofcontents` - Automatically generates the table of contents page
* `\bibliography` - Generates the References section
* `\listoftables` - Generates a list of all the tables
* `\listoffigures` - Generates a list of all the figures


For more info on LaTeX and more of its built in commands, click [here](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes).
