# Circular Biology
This page is a tutorial to learn about and practice the statistical analysis of circular (orientation) data in biology.  Circular statistics are often employed to analyze various types of biologic data that is described, for example, by angles (directions) or periodic processes (eg., circadian rhythyms or lunar cycles).  This tutorial is designed for use in R, which has already been introduced into this class.

Before we begin, and in case you have not used GitHub before, GitHub is a useful resource for designing and sharing comuter code, tutorials, and data with others.  Below, will be various text describing the steps to be performed.  Additionally, you will encounter gray boxes.  These gray boxes contain the actual code that can be used in R.  Lines of code that are ignored by R begin with an hashtag (#), and the other lines contain the commands.  For example:
```R
# Make a vector
data = c(1, 2, 3, 5:11)

# Calculate the mean
mean(data)
```
The commands in the gray box above can be directly copied and pasted into an R terminal, or typed by hand.  Additionally, you may find links to datasets or websites underlined in blue.  For example, you can find more information on circular statistics at [this wikipedia page](https://en.wikipedia.org/wiki/Directional_statistics). If you have any additional questions about GitHub or this tutorial, please let me know during the exercise.  Have fun!

## Part 1
In order to make some specialized commands available to us to analyze circular data, we are going to install a 'package'.  The package is called ['circular'](https://cran.r-project.org/web/packages/circular/index.html), and its manual is available [here](https://cran.r-project.org/web/packages/circular/circular.pdf).

First, open your R terminal (or R studio), and enter the following commands:
```R
# Install R package
install.packages('circular')

# Load the package
library(circular)
```

