# New Jersey Newspapers

A short classroom exercise analyzing New Jersey newspaper metadata. This is adapted from Ryan Cordell's "US historical newspapers metadata experiments" at <https://github.com/rccordell/us-newspapers-1689-2009>.

To run the code chunks interactively, do the following steps.

1. Go to <https://rstudio.cloud/> and create a free account (use Google credentials to simply login).
2. In the workspace area of RStudio Cloud, click the down arrow next to "New Project" in the upper right. Select "New Project from Git Repository." In the URL field, copy/paste <https://github.com/giannetti/nj-newspapers> and click "OK."
3. When "nj-newspapers" deploys as a new project, have a look at the "Files" pane in the lower right. Click to open `nj-newspapers.Rmd`. This is an R Markdown file with interactive code chunks and commentary. It will open in the scripts pane in the upper left. 
4. You can run each code chunk by clicking the little green arrow in the upper right. The first chunk has all the required third-party libraries and needs to be run in order for subsequent code chunks to work. When you do so, an object called `nj-papers` will appear in your Environment pane in the upper right. Click on it to open a spreadsheet view that you can scroll through. 
5. Subsequent code chunks should be fairly self-explanatory. Run them and explore the resulting visualizations for what they tell us about the history of New Jersey through its newspapers!

![Interface of RStudio Cloud with an indication of where to click to run code chunks](https://github.com/giannetti/nj-newspapers/blob/master/rstudio-cloud-interface.png)

There is a web version of handout [here](https://htmlpreview.github.io/?https://github.com/giannetti/nj-newspapers/blob/master/nj-newspapers.html), but it is missing the last two interactive plots for complicated JavaScript reasons. 
