Overview
===================

This is an example of a Tables Rmd with separate Rmds for the individual tables. `Table1.Rmd` is a simple table. `Table_Counts` is a table function that is then called to make tables with the same format but different input data. For this example, I am only going to use **flextable** packages. 

Also note, best not to use chunk labels in your Rmd children. It's too easy to get duplicate labels accidentally.

Instructions
===================

Open Report_with_Tables.Rmd and knit to Word (or html).

It has children

* tables/Table1_flex.Rmd
* tables/Table_Counts_flex.Rmd
* figures/Figure1.Rmd

It uses a Word template file to format the Word file:

* template.docx

Note, there is a bug in **flextable** and it won't use a template file with the file ending `*.dotx`. So you need to rename your template file to `.docx`.
