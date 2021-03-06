## Data analysis in social science 3, University of Exeter (2020)

### Module outline

#### Classes

- Wednesday, 9.30-11.30am, Queens LT4.2

#### Lecturer

- Dr Alexey Bessudnov (a.bessudnov [at] exeter.ac.uk)
- Teaching assistant: Yiyang Gao (yg319 [at] exeter.ac.uk)

#### Office hours

- Location: Clayden 1.05
- Monday, 10-11am
- Friday, 10-11am
- Yiyang's office hours: Clayden, Wednesday, 11.30am - 1.30pm

#### Aims of the module

This is a fourth module in the data analysis in social science series. In the Introduction to Social Data you learned the basics of descriptive statistics and R. Data Analysis 1 introduced you to statistical inference. Data Analysis 2 covered linear regression analysis. In Data Analysis 3 we are not going to learn new statistical techniques, but will focus on how to apply the techniques you already know to the analysis of real-life data sets and how to produce good statistical reports.

This is a skill that you may need in a variety of jobs where data analytic expertise is required, such as market analysis, policy analysis in various fields, web analytics, data journalism, academic research, etc.

You already know how to use R to describe data and estimate simple statistical models. However, real-life data rarely come in the form of a perfectly formatted csv file ready for the analysis. The real life data sets often need to be reshaped, merged, recoded, aggregated and modified in various ways before you can even start your analysis. Unless you know how to do this you will not be able to conduct independent statistical analysis.

In this module we will use data from the Understanding Society, a large household panel study conducted in the UK. We will work with longitudinal data, which introduces a number of technical challenges.

We will use R, and you are expected to know the basics of data analysis in R already. The pre-requisites for this module are POL/SOC1041 and POL/SOC2077.

The only way to learn data analysis is to do data analysis. I will not be able to teach you this, but I can guide your independent learning. I use the "flipped classroom" model of teaching. This means that you are expected to read and master the required material BEFORE you come to class and we will often use class time to do exercises and check solutions rather than introduce new material.

#### Software

You will need to use your own laptops in class. Plese install the following software.

- [R](https://www.r-project.org/) (please update your distribution if you have got it already installed)
- [R Studio](https://www.rstudio.com/)
- [Git](https://git-scm.com/)
- [LaTeX](https://www.latex-project.org/)

All this software is free. 

#### Attendance

This is a technical module, and it will require effort and time commitment from you. As with other technical skills, missing some initial bits means that you may not be able to catch up. Attendance in this module is crucial. If you do not attend classes you will not be able to do well in this module.

#### Assessment

The assessment for this module is a statistical report of 2,000 words (50% of your mark) and five short statistical assignments (10% each).

Statistical assignments will usually be programming exercises. You will need to complete them using R and Github and submit using Github Classroom so that each assignment is a separate repository. You will also need to submit links to your repositories via eBart. I will explain the procedure in more detail in class, and we will have a test (not graded) submission to make sure you understand how it works.

I will release problems for assignments 6 days before each deadline. Assignments must be your individual work and you are not allowed to work on them together with other students.

The deadlines for statistical assignments are as following.

- Test submission: 28 January, 2pm (formative)
- Assignment 1: 4 February, 2pm
- Assignment 2: 11 February, 2pm
- Assignment 3: 18 February, 2pm
- Assignment 4: 3 March, 2pm
- Assignment 5: 17 March, 2pm


The marking criteria for statistical assignments are correctness of your code and of substantive interpretations (where applicable).

The 3-week turnaround rule applies to statistical assignments, but our goal is to mark them and give you feedback as soon as possible.

For the final statistical report you will conduct independent analysis of the Understanding Society data and produce a report of 2,000 words describing the results of your analysis.

The deadline for the final statistical report is 28 April, 2pm. I will publish more details describing your task at least one month before the submission deadline. You will receive your marks and feedback by 12 June.

The marking criteria for statistical reports are the following: originality of approach, complexity of analysis, correctness of code, correctness of interpretations, knowledge of background literature, style and accuracy.

#### Students with ILP

Students with ILPs sometimes request extensions for statistical assignments. Please note that you can only do the same assignment as other students if your extension is for no longer than one week. All deadlines for statistical assignments are set on Tuesdays, and the answers will be discussed in class on Wednesdays the following week. After the solutions have been discussed in class you can no longer submit the same assignment. In this case you need to contact me as soon as possible and you will be given a new assignment.

#### Homework

I assign homework for each class and you need to complete it before coming to class.

#### Syllabus plan 

The plan below is flexible and I may change some topics and dates as we proceed.

- 15 January. Introduction to the module.
- 22 January. Data analysis workflow. Reproducible research. R Markdown. Understanding Society data.
- 29 January. Data transformation.
- 5 February. Relational data.
- 12 February. Tidy data and reshaping.
- 19 February. Data visualisation (1).
- 26 February. Data visualisation (2).
- 4 March. Conditional statements and iteration.
- 11 March. Functions.
- 18 March. Data types. Factors.
- 25 March. Strings.

#### Reading list

The module has a website: <http://abessudnov.net/dataanalysis3/>. Please note that the website accompanied the module as delivered in 2018, and in 2020 we will do some things differently.

The main text for this module is Grolemund and Wickham's *R for Data Science*.

- G.Grolemund & H.Wickham. R for Data Science. Freely available at <http://r4ds.had.co.nz/>.

Solutions for the exercises in R for Data Science:

- J.B.Arnold. [R for Data Science: Exercise Solutions](https://jrnold.github.io/r4ds-exercise-solutions/)

For details on how to use R Markdown see:

- Y.Xie, J.J.Allaire, G.Grolemund. (2018). [R Markdown: The Definitive Guide](https://bookdown.org/yihui/rmarkdown/).

The guide on using Git and Github with R Studio:

- J.Bryant et al. [Happy Git and GitHub for the useR](https://happygitwithr.com/).

Data visualisation.

- H.Wickham. (2009). ggplot2: Elegant graphics for data analysis. N.Y.: Springer. [Available in the university library as an ebook.]
- W.Chang. (2019). R Graphics Cookbook. 2nd ed. https://r-graphics.org/
- K.Healy. (2018). Data Visualization: A Practical Introduction. Princeton University Press. You can access the draft of the book here: https://socviz.co/  and the code for the graphs is available here: https://github.com/kjhealy/dataviz .
- The BBC Visual and Data Journalism cookbook for R Graphics: https://bbc.github.io/rcookbook/

R Programming.

- R.Peng. (2016). R Programming for Data Science. https://bookdown.org/rdpeng/rprogdatascience/

- H.Wickham. (2014). Advanced R. http://adv-r.had.co.nz/

Machine learning.

- G.James et al. (2013, 8th printing 2017). An Introduction to Statistical Learning with Applications in R. Springer. Freely available at http://www-bcf.usc.edu/~gareth/ISL/
- The caret package. Online textbook: http://topepo.github.io/caret/index.html

There are many other resources that can help you with R. [DataCamp](https://www.datacamp.com/) is an online learning platform that covers most topics in this module. Also see a list of other resources here <https://www.tidyverse.org/learn/>.

Full documentation for the *Understanding Society* is available at <https://www.understandingsociety.ac.uk/>.

