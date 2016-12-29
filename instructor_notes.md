---
layout: lesson
title: Instructor notes
root: .
---

## Instructor notes

### Lesson purpose

The purpose of this lesson is [tofill]

-----------
> ## Learning Objectives
> ### 00-before-we-start.Rmd
> - Describe the purpose of the RStudio script, console, environment, and plot windows.
> - Organize files and directories for a set of analysis in an R Project.
> - Define the following terms as they relate to R: script, function, working directory, assign, object, variable.
> - Assign values to variables.
> - Call functions with zero or more named or unnamed arguments.
> - Use the built-in RStudio help interface to search for more information on R functions.
> - Demonstrate how to provide sufficient information for troubleshooting with the R user community.
> ### 01-intro-to-R.Rmd
> - Solve mathematical operations in R.
> - Assign values to objects and variables in R.
> - Describe what vectors are and how they are manipulated in R.
> - Inspect the content of vectors in R and manipulate their content.
> - Extract values from vectors in R.
> - Employ logic (i.e. TRUE, FALSE) to subset data in a vector.
> - Analyze vectors with missing data
> ### 02-starting-with-data.Rmd
> - Describe what a data.frame is.
> - Summarize the contents of a dataframe in R.
> - Load external data from a .csv file into R.
> - Manipulate categorical data in R.
> ### 03-data-frames.Rmd
> - Read data from a file into a data.frame.
> - Change how character strings are handled in a data.frame.
> - Summarize the size and data types of a data.frame
> - Write a command to print a sequence of numbers.
> - Subset data in a data.frame.
> ### 04-dplyr.Rmd
> - Recall the six data manipulation ‘verbs’ in the dplyr package and know what they do.
> - Select subsets of columns and filter rows in a data.frame according to a condition(s).
> - Employ the ‘pipe’ operator to link together a sequence of dplyr commands.
> - Employ the ‘mutate’ command to apply functions to existing columns and create new columns of data.
> - Export a data.frame to a .csv file.
> ### 05-visualization-ggplot2.Rmd
> - Produce scatter plots, bloxplots, and time series plots using ggplot.
> - Set universal plot settings.
> - Modify the aesthetics of an existing ggplot plot (including axis labels and color).
> - Build complex and customized plots from data in a dataframe.
> ### 06-r-and-sql.Rmd
> - Access and run a SQL query in R.
> - Create a database from an existing .csv file using SQL syntax.
> - Recognize how scripted database interactions enhance the reproducibility of data analysis.
 
-----------

### Narrative

**In 00-before-we-start.Rmd**

- Introduce in short but with clarity what is the relationship between R (programming/scripting language)
and RStudio (wrapper or Integrated Development Environment).
- Emphasize that it is good practice to create projects and organize files within subfolders
in the same working directory in order to achieve reproducibility and portability.
- Introduce the 4-panes subdivision of the RStudio interface: 
the editor for your scripts and documents (top-left),
the R console (bottom-left),
your environment/history (top-right),
and your files/plots/packages/help/viewer (bottom-right).

**In 01-intro-to-R.Rmd**

**In 02-starting-with-data.Rmd**

**In 03-data-frames.Rmd**

**In 04-dyplyr.Rmd**

**In 05-visualization-ggplot2.Rmd**

**In 06-r-and-sql.Rmd**

**Concluding points**  

### Potential issues & solutions

### Technical Tips and Tricks

Show how to use the 'zoom' button to blow up graphs without constantly resizing windows

Sometimes a package will not install, try a different CRAN mirror 
- Tools > Global Options > Packages > CRAN Mirror   

Alternatively you can go to CRAN and download the package and install from ZIP file
-   Tools > Install Packages > set ti 'from Zip/TAR'

### Other Resources

##
