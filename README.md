# r-seminar
Repository for the R seminar (Spring 2021, University of Basel)

li## Schedule and assignments

New WPAs and readings will be uploaded weekly, so check back regularly.

| Week | Date | Topic | Texbook readings | Assignment (in class) | Answers |
| ---- | ---- | ----- | ---------------- | --------------------- | ------- |
| 1 | 2 March | Introduction | No readings | [WPA 1](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa1.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa1_answers.html) |
| 2 | 9 March | Basic R | [Chapter 1](https://moderndive.com/1-getting-started.html) | [WPA 2](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa2.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa2_answers.html) |
| 3 | 16 March | Data visualization | [Chapter 2](https://moderndive.com/2-viz.html) | [WPA 3](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa3.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa3_answers.html) |
| 4 | 23 March | Data wrangling | [Chapter 3](https://moderndive.com/3-wrangling.html) | [WPA 4](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa4.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa4_answers.html) |
| 5 | 6 April | Importing data | - | [WPA 5](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa5.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa5_answers.html) |
| 6 | 13 April | Tidying data | [Chapter 4](https://moderndive.com/4-tidy.html) | [WPA 6](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa6.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa6_answers.html) |
| 7 | 20 April | Writing Functions and Loops | ??? | [WPA 7](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa7.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa7_answers.html) |
| 8 | 27 April | Linear and logistic regression | [Chapter 5](https://moderndive.com/5-regression.html) | [WPA 8](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa8.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa8_answers.html) |
| 9 | 4 May | Multiple regression and ANOVA | [Chapter 6](https://moderndive.com/6-multiple-regression.html) | [WPA 9](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa9.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa9_answers.html) |
| 10 | 18 May | Multilevel regression | ??? | [WPA 10](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa10.html) | [Answers](http://htmlpreview.github.io/?https://github.com/laurafontanesi/r-seminar/blob/main/html/wpa10_answers.html) |
| 11 | 25 May | Group project 1 | ??? | [Group project](https://nbviewer.jupyter.org/github/laurafontanesi/r-seminar/blob/main/notebooks/group_project.ipynb)
|  |
| 12 | 1 June | Group project 2 | ??? |  |  |

## Important Links
Link | Description 
-------------------- | ----------------------------------- 
[RStudio](https://rstudio.com/products/rstudio/download/) | Download link for RStudio. Only necessary if you are using it on your own computer and not in class.
[Textbook (Statistical Inference via Data Science, by Chester Ismay and Albert Y. Kim)](https://moderndive.com/) | For weekly readings.
[Base R cheat sheet](https://rstudio.com/wp-content/uploads/2016/10/r-cheat-sheet-3.pdf) | A handy R guide.
[Tidyverse cheat sheets](https://medium.com/@brianward1428/introduction-to-tidyverse-7b3dbf2337d5) | Quick reference guide for tidyverse, with different cheat sheets separated by topic.
[ggplot2 reference guide](https://ggplot2.tidyverse.org/reference/index.html) | Your main reference guide for plotting.

**Note**:
If you are still experiencing issues with ggplot or tidyverse, do the following (in this order):
1) re-install R: https://stat.ethz.ch/CRAN/
2) re-install RStudio: https://rstudio.com/products/rstudio/download/
3) in RStudio, type `install.packages("tidyverse")`

#### Get Jupyter notebooks running on your laptop
- Download Anaconda (it's available for Windows, Mac and Linux systems): https://www.anaconda.com/distribution/
- Follow these instructions: https://docs.anaconda.com/anaconda/navigator/tutorials/r-lang/
- You can simply download the course's notebooks from https://github.com/laurafontanesi/r-seminar: Click on Clone or download > Download as ZIP. Otherwise, if you are familiar with git, you can clone the repository and pull the new material each week.
- Now you should be able to open the WPA notebooks from within Anaconda, as explained in the link above

## Course Description
R is one of the most popular statistical languages for both academic researchers and data analysts working in the industry. The reason why is simple: R is free, easy to use and incredibly powerful. With R you can generate and manipulate data, conduct analyses, create plots and even write documents. The goal of this course is to introduce you to R so you can apply it to your current and future research. In this course, you will learn how to use R to conduct all steps of your data analysis, from loading data to performing analyses, to producing figures.

## Weekly Programming Assignments (WPAs)
During each class, you will work on a series of programming tasks called **Weekly Programming Assignments (WPA)**. You can do this alone, but I encourage you to discuss and/or work with your peers. It is however very important that each student's work is his/her own. Do not turn in any assignments that you did not contribute to or do not fully understand.

By the end of the lesson, you should email your WPA to me to receive credit. While I will keep track of how often you submit your WPAs, I will *not* grade them. You should however try to reply to each of the questions in the assignment. When you are not able to, I will be there to answer any doubt or question about the code. These assignments are meant as a practice to learn-by-doing the class' material.

As a final assignment, you will have to run a data analysis flow from the beginning to the end. More info on this will be provided later during the course.

## Grading
This is a pass / fail course. To pass the course, you should turn in your WPAs, miss not more than 2 classes, and pass the final assignment.

## Tips
Learning R will be challenging, but ultimately rewarding. However, it will be a lot easier if you ask questions. Here are the best ways to ask.

**Use the help function**
If you are unsure how a function works or what its doing, type ?functionname into the console (functionname should be the name of the function e.g. ?mean). Every function has documentation, and this command will bring it up. If you don't know the exact function name, you can also type ??thingIamlooking (.e.g. ??mean) to perform a search for related documentation. See [this page](https://www.r-project.org/help.html) for how to get help in R.

In RStudio, I suggest to activate the help pane (View>Panes>Show All Panes), and always search for functions, especially when you are using them for the first time. This will also help you to understand how functions are organized in packages, and develop a better understanding of your R environment.

**Google Everything**
If you have a problem (particularly outside class) Google it. Almost every question you have, someone else has asked at some point. This applies particularly to R. There are a lot of good forums you might end up on, like [stackoverflow.com](http://stackoverflow.com/tags/r/), or [stats.stackexchange.com](http://stats.stackexchange.com/questions/tagged/r), where people provide detailed answers. You also might find documentation and functions you couldn't find using the internal help or materials from other courses. I Google R and stats related questions daily and am constantly finding innovative answers and new functions. Just keep in mind that there is no point copying someone else's code if you don't understand how it works and how to adapt it to your circumstances.

[For example](http://letmegooglethat.com/?q=load+csv+in+R)

**Ask, ask, ask!**
Thats why I'm here. If you don't know what you are doing or why something doesn't work (or does work), or maybe you do know what you are doing but you want to make it more efficient, please do not hesitate to ask questions. As this is meant to be a more practical seminar and we are somewhat limited by the online format, it is very important that we all make an effort to communicate with each other.

**Take notes**
Even during the graded assignments, you can consult all the material you want. However, sometimes having too many resources to look at is not optimal, since you might end up wasting a lot of time searching for what you need all the time. What I suggest you to do, is to keep notes on the commands you find most difficult to remember or on examples that you find particularly useful. This will also help you organize the material in a way that might be better for you, compared to how I will present topics during the course or how it is presented in the text book.

## R and WPA guidelines
1. Be sure you save your script often.

2. Keep your script clean. Comment out all the text that it's not R-interpretable by putting an `#` in front. One should be always able to run your script from beginning to end without getting errors. If you have code that didn't work (that did give you an error), comment it out. You can then explain in the comment what you think went wrong. Never paste the output in your script, unless it's required in a specific question. In that case, be sure to comment it out.

3. Print the output of all new lines of code, to check if they do what you are actually meaning them to. Re-run your script from the start every time you make significant progress, or to test a new chunk of code before starting with the next exercise. Many bugs can be detected by "starting fresh".

4. Always clean your workspace at the beginning of your script, using the command `rm(list = ls())`. This avoids forgetting old variable names that could mess up with your code. 

5. Avoid using the console window and RStudio "buttons" (such as the ones to import data or to clean your workspace). It's always better to have all the commands that you used written down in your script so that you can easily retrace what you have done up to that point. Plus, that makes your script entirely reproducible by another user (e.g., me). That's also why we use R instead of for example SPSS.

6. Keep all your scripts in one folder, of which you always know the location and the path in your operating system. You can name the folder as you please (e.g., "r-course") as long as you remember it. Inside this folder, create a sub-folder called "data", where you will download/save all the datasets that we will use throughout the course. Be sure that you never change the location of this folder and sub-folders/files. This will ensure that you will always be able to re-run your scripts at any point in time. You can also have a look at [Projects](https://support.rstudio.com/hc/en-us/articles/200526207-Using-Projects), which help to keep separate R projects organized.

7. Use code completion (Tab key) as much as possible. This not only speeds you up, but it's incredibly helpful to avoid typos. Also, it allows you to explore possible arguments within a function you didn't know about, and also know whether a specific function you are planning to use is even loaded in your current environment. Code completion is also your best friend when specifying the path of a file you want to load: 
- On Mac, you can start from `read.csv('~/')` (or similar functions for loading data) and press Tab, to start navigating from your home folder
- On Windows, you can do the same, but starting from `read.csv('C:\Users\')`

8. Use the help window in RStudio as much as possible. Search for new functions when you use them for the first time. This will massively improve your knowledge of R, by giving you more ideas of what is even possible to do.

9. Even though it is possible to specify functions' arguments without naming them, try to avoid that as much as possible. It's very easy to confuse the order of arguments and get unexpected results. For example, type `seq(from=0, to=10, by=1)` instead of `seq(0, 10, 1)`. It also makes it more readable for the "future you" and a different user (e.g., me).

10. Either use `=` or `<-` for assignments, but do it consistently (e.g., either `a = 4` or `a <- 4`), and use `_` instead of `.` in identifiers (e.g., `my_variable = 5` instead of `my.variable = 5`).

*Here is an example of how your `wpa_1_LastFirst.R` file could look like:*

```{r}
# Assignment: WPA 1
# Name: LAST, FIRST
# Date: DAY MONTH YEAR

rm(list = ls()) # clean workspace

# TASK A1
# Add 1 to 1
1 + 1

# TASK A2
# Draw 100 samples from a standard normal
x = rnorm(100)

# TASK A3
# Conduct a t-test. Write down the p-value.
t.test(x)
# p = .04

# TASK A4
# What is the height of dogs that weigh more than 5 kg?
# I tried dogs[dogs['weight'] > 5, height] but didn't work. I suspect that there is a problem with height.
```