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


| Function    |            Purpose          |                      Example |
|-------------|-----------------------------|------------------------------|
|?            |           Access help files |                    ?boxplot|  |
|#            |            Add comments     |                     #Add your comments here
|boxplot      |           Makes a boxplot   |                    boxplot (y) boxplot (y~factor (x))|
|log          |            Natural logarithm |                    log (2) |
|log10         |           Logarithm with base 10 |                log10 (2) |
|library       |          Loads a package  |                      library (qstat)|
|setwd         |          Sets the working directory |            setwd ("C:/AnyDirectory/")|
|q( )            |           Closes R         |                       q( ) |


## Getting Data into R ##

**Assigning variables:**
```
 a <- 59
 b <- 55
 c <- 53.5
```
In R, variables are assigned like this. Instead you can use the **=** symbol instead of **<–**.
The above example explains that **a** takes the value of 59 and similarly b and c.

The output of the above code is:
```
a
[1] 59
```
same as the above format for b and c. To see the values of b & c, type b and c.

In R, We have some inbuilt functions like **sqrt**, **mean**,**sum**,**min** ,**max** ,**median** ,**var**, **sd** and others. We can use this and perform operations on the variables and data.

```
sq.str <- sqrt(a)
```
Here the above snippet explains that the sqrt of **a** value is stored in the variable **sq.str**

**Note:**
The dot is also a part of the variable name. Try the snippet and check it out for yourself.

However, you should avoid names that contain characters like £, $, %, ^ , *, +,-, ( ), [ ] #, !, ?, <, > etc.

**Concatenating Data with the c Function :**

R provides us with c() function, where c stands for concatenate. It isused as follows 

```
test <- c(59, 55, 53.5, 55, 52.5, 57.5, 53, 55)
```
**Output**
```
test
[1] 59.0 55.0 53.5 55.0 52.5 57.5 53.0 55.0
```

It helps us in assigning multiple values to a single function at once without the need of assigning variables and alloting values to each of them.

```
> test [1]
[1] 59
```
This gives the value 59.

```
> test [1 : 6]
[1] 59.0 55.0 53.5 55.0 52.5 57.5
```
This prints the values from First index to the sixth one.

```
> test [-2]
[1] 59.0 53.5 55.0 52.5 57.5 53.0 55.0
```
Hence, the minus sign omits a value. The second index is omitted and the remaining values are displayed.


**The complete guide is coming soon. I'll be heavily updating the notes soon..**












