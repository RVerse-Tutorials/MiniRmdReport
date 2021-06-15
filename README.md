Overview
===================

This is an example of a Tables Rmd with separate Rmds for the individual tables. `Table1.Rmd` is a simple table. `Table_Counts` is a table function that is then called to make 5 tables with the same format but different input data. For this example, I am only going to use `kable()` for all output types. See `Tables.Rmd` in the main folder for examples of using the **kableExtra*` and** and **xtable** packages. 

The `Table_Counts.Rmd` shows you how to include a page break in your Word doc between tables. Also note that I use `format="pandoc"` for the table. That works for Word in my experience.

Also note, best not to use chunk labels in your Rmd children. It's too easy to get duplicate labels accidentally.

**Make sure these files are in your working directory. You may need to set the working directory to Report_with_Tables.**

Instructions
===================

Open Report_with_Tables.Rmd and knit to Word.

It has children

* Table1.Rmd
* Table_Counts.Rmd