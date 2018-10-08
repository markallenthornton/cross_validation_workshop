# Cross-validation workshop
### Rcode and HTML markdown for tutorial in the Harvard Methods Dinner series

Cross-validation represents a class of powerful procedures for measuring the performance of statistical models. In cross-validation,
a sub-sample of a data set is used to "train" a model - e.g., setting parameters - and this trained model is then used to made predictions
in another, independent subsample of the data. By training and testing in independent data, cross-validation provides an estimate of
the generalization performance of a model - how well it would work when applied to an entirely new data set of the same type. This 
helps to minimize the risk of trusting an "overfitted" model which captures a particular data set unrealistically well by capitalizing on chance. This workshop will describe how cross-validation work, with real and artificial examples examined in R.

### Installation

First, please install [R](https://cran.r-project.org/) and [RStudio](https://www.rstudio.com/products/rstudio/download/#download).

Then, clone this repository to your local machine, and open "cross_validation_workshop.Rmd" with RStudio. From the "Run" dropdown menu in the upper left pane, select "Run All". You may have to install some packages if you've never used RMarkdown before. When the script completes, save the .Rmd file, and then select "Preview" to view the R Notebook. To make changes, edit the code in the .Rmd file, re-run the corresponding code-chunk(s), and then save changes - the preview will update automatically.

Alternatively, a static version of the R Notebook can be viewed directly through your web browser by downloading the file ending in ".nb.html" and then opening it with the browser of your choice (e.g., Firefox). Viewing this version does not require R/RStudio, but changes cannot be made to the code.



