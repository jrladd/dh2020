---
layout: post
title:  "3. Tabular Data in Spreadsheets"
date:   2020-10-02 14:52:58 -0500
---

Last week you worked with text data on the command line. This week, you'll explore tabular data using an equally ubiquitous tool: spreadsheet software. Specifically, you'll work with some humanities data in Google Sheets.

Spreadsheets are commonly used to collect and store DH data, especially in the early stages of a project, and you'd be surprised how much you can do with a spreadsheet without needing a more complex data analysis tool. I used to think of spreadsheets as being primarily useful for numerical data, but I've since learned a lot about how to use them with categorical, text-based data.

A lot of digital humanities work involves simple counting operations: grouping and splitting data by conditions and finding out counts and percentages based on various categories. The techniques we'll cover in this workshop, especially in the `QUERY()` function in Google Sheets, mimic the principles of database querying. These same principles (selection, conditions, grouping) can be found in Structured Query Language (SQL), the most common language for querying relational databases, as well as [R](https://rstudio.com/) and Python (in its R-like data analysis library, [pandas](https://pandas.pydata.org/)), even if the exact syntax for queries will look slightly different in each.

To begin follow [this tutorial](https://jrladd.com/spreadsheets.html) on working with tabular data in Google Sheets. Look over the [live sample data](https://docs.google.com/spreadsheets/d/1LnbU9ONCUxRKu7aDklfhDBVbH_5scckAF_4SFFyT3CE/edit?usp=sharing) that the post links to and play around with the examples.

Once you're comfortable with the basics, you can try it out on some real world data. [Download this CSV (comma-separated value) file containing a list of 70,000+ registered elevator devices in New York City](https://github.com/datanews/elevators).[^1] Upload that CSV to your own Google Sheet (and let me know if you have any questions about how to download the data and get it into a sheet). Once it's there, you can use the skills you've learned to develop a small research question about the dataset and answer it using a `QUERY()` or `COUNT()` function. You might want to know how many active passenger elevators there are in each borough, or how many elevators are currently undergoing maintenance. [A quick tip: use the + sign at the bottom of Google Sheets to open a new individual sheet to write your functions.]

Consider too what this data can and can't tell you about New York's elevators. How does it help us understand the city's vertical space? What kinds of data are or might be missing? What if anything can this data say about accessible spaces in New York?

[^1]: I got this data from the [Data is Plural](https://tinyletter.com/data-is-plural) archive of data sets, which is ironically kept in... a Google Sheet.
