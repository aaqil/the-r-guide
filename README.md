# the-r-guide
**A guide for statistical computing and graphics.**

## Downloading and Installing R ##
 Go to https://www.r-project.org/
 
 On the left side of the page,you will find CRAN.
 This stands for Comprehensive R Archive Network, and it allows selection of a regional computer network from which you can download R.
 Choose the location nearest to you. 
 
 Clicking the Linux, MacOS X, or Windows link opens the window that allows us to choose between the base installation file and contributed packages. We discuss packages later. For the first time, click on the link labelled base.
 
 After the installation is over, you will have a console and a terminal. Console is like a interpretor where you can perform simple arithmetic and basic operations.
 
 Later download the R-studio(it's the official IDE by R language) which makes your job easier. Download it from https://www.rstudio.com/products/rstudio/download/ <br>
 
 RStudio is a set of integrated tools designed to help you be more productive with R. It includes a console, syntax-highlighting editor that supports direct code execution, and a variety of robust tools for plotting, viewing history, debugging and managing your workspace.<br>
 
 Now you are all setup to work on R.
 
 For better Productive Work I prefer R studio than other editors and IDE's.
 
 **Editor:**
 For editor use  Tinn-R. Go to https://tinn-r.soft112.com/ and download. And you can use **RWindEdt** (this is an R package).
 
**Setting the Working Directory:** <br>
```
> setwd(file = "C:\\AnyDirectory\\")
```
## Basics:
```
| Function    |            Purpose          |                      Example |
|-------------|-----------------------------|------------------------------|
|?            |           Access help files |                    ?boxplot|  |
|#            |            Add comments     |                     #Add your comments here
|boxplot      |           Makes a boxplot   |                    boxplot (y) boxplot (y~factor (x))|
|log          |            Natural logarithm |                    log (2) |
log10         |           Logarithm with base 10 |                log10 (2) |
library       |          Loads a package  |                      library (qstat)|
setwd         |          Sets the working directory |            setwd ("C:/AnyDirectory/")|
q             |           Closes R         |                       q()
```

## Getting Data into R ##
