#Short Tutorial about Machine Learning and Reproducible Scripting

This is a short tutorial about machine learning and reproducible scripting. For the tutorial, we use a subset of the Wisconsin Breast Cancer Dataset (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).

In order to run this, you will need to have Rstudio, a recent version of R (3.0 or greater) and the following packages installed.

- knitr
- MASS
- tree

You will open the RMarkdown (`.Rmd`) files, which consist of the following files:

- `irisLdaCTrees.Rmd` - Example Rmarkdown showing how to run Linear Discriminant Analysis (lda) and Classification trees on the iris dataset.
- `ldaAssignment.Rmd` - Worksheet to fill out for LDA analysis on Breast Cancer Dataset. Adapt code from `irisLdaCTrees.Rmd` and place in here with your interpretation of the results. When you're done, you can knit the results using the `knit` command above the window.
- `treeAssignment.Rmd` - Worksheet to fill out for

Data Files consist of the following

- `data/wdbc-readme.txt` - Readme file for the Wisconsin Dataset.
- `data/trainData.txt` - Tab Delimited Data File for training your classifiers.
- `data/testData.txt` - Tab Delimited Data File for testing your classifiers.

For more info about Rmarkdown, check out my tutorial: http://github.com/laderast/magic-of-markdown
