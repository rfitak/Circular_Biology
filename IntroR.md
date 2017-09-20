# An Introduction to R
This tutorial introduces the statistical and graphical software suite R.  R is free, open-source software and one of the most powerful tools in the scientific and research community.  Although R does require some basic computer lingo, it can be learned quickly for most base-level analyses and plotting functions.

### Downloading and Installing R
R, and its graphical user interface (GUI) R-Studio, can be downloaded and installed from its website: [The R Project](https://www.r-project.org).  Unfortunately, a detailed set of installation instructions will not be provided here since it varies considerably depending on the operating system you have (i.e., Windows, Max, Linux).  However, the homepage for R at the link above provides many downloading locations (also called mirrors) at the [download R](https://cran.r-project.org/mirrors.html) link, which should redirect you to a page with downloading links and instructions for various operating systems (e.g., [Berkely mirror](https://cran.cnr.berkeley.edu)).

### Navigating R
Once R or R-studio is installed, open it (or run the terminal version).  R will have a prompt, usually indivated by '>', where it is expecting you to provide commands.  Below, you will find some example commands with descriptions to help introduce you to the basics. You will encounter these commands in gray boxes. These gray boxes contain the actual code/functions that can be used in R. Lines of code that are ignored by R begin with an hashtag (#), and the other lines contain the commands (also called functions). For example:
```R
# Get my current folder location
getwd()
```
The function ```getwd``` in the gray box above can be directly copied and pasted into an R terminal, or typed by hand.  After entering the command, press the \<enter\> key.  The above command should produce the location, or path, to the folder of your computer that you are currently working in.  My results was:  
[1] "/Users/rfitak"  
You can change to a different folder on your computer by giving a different path to the function ```setwd```:
```R
# Change to the folder called ecaves
setwd("/Users/ecaves")
```
If you are not sure about how to use any function, look at the manual:
```R
# Get the help manual for the function 'setwd'
?setwd
```
