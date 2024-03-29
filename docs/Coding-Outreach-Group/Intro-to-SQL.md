---
layout: default
nav_order: 5
parent: Coding Outreach Group
title: Intro to SQL Workshop
---

# COG Summer Workshop 2023

{: .label .label-blue }
New
# Intro to SQL
07/27/2023

__**Content creators:**__ Billy Mitchell & Katie Jobson

## Description
SQL is a common language used in data science jobs, designed to manage data held in a relational database management system. This workshop will aim to detail the uses of SQL in industry and give a brief introduction to how to use it. 

## Prerequisites
This workshop demands that users:
1. Have [RStudio](https://posit.co/download/rstudio-desktop/) downloaded
2. Have a general knowledge of data structures in languages like Python and R

    
## Workshop objectives:
1. Have a basic understanding of SQL and what it is used for
2. Be able to set up SQL in other porgrams suchs as RStudio and Jupyter Notebokks
3. Become familiar with some basic SQL functions

## Workshop materials:
- [Notebook Viewer](https://kjobson-neuro.github.io/rmd/sql.html)


## What We Won't Cover:
We will not be covering basic coding ideas or basic knowledge of RMarkdwon. We won't be covering how to use SQL Servers on their own. We will only be touching briefly on more advanced SQL functions; this will primarily serve as an *introduction* to SQL and how to use it in RStudio - for more advanced functions, we will refer to some online resources. 

If you would like to use Jupyter Notebooks to run SQL commands, we will be covering how to set it up, but not how to execute commands. If you need a tutorial on how to use Jupyter Notebooks, please see [this](https://github.com/TU-Coding-Outreach-Group/cog_summer_workshops_2021/tree/main/jupyter-notebook) previous workshop by Kim Nguyen. Otherwise, for more information on how to use SQL in Jupyter Notebooks, please see [this](https://docs.devart.com/odbc/sqlserver/python.htm) tutorial. For more information, please see the [MS SQL Website](https://learn.microsoft.com/en-us/sql/connect/python/pyodbc/step-3-proof-of-concept-connecting-to-sql-using-pyodbc?view=sql-server-ver16) on how to utilize this function. 

## Outline
| Section                | Description                                | Time   |
|:----------------------:|:------------------------------------------:|:------:|
| Intro                  | What is SQL and why would we wse it?       | 15 min |

| Setup                  | Setting up an SQL Server                   | 25 min |
| Code                   | Coding in SQL                              | 15 min |  
| Integration & Analyses | Taking data from SQL and analyzing it in R | 15 min |  
| Advanced Functions     | Briefly introduce more advanced functions  | 15 min |  
| Conclusion             | Wrapping up                                | 5 min  |  
| Q&A                    | Questions?                                 | 30 min |  

## Additional Resources
[W3schools tutorial on SQL](https://www.w3schools.com/sql/)    
[Khan Academy tutorial on SQL](https://www.khanacademy.org/computing/computer-programming/sql)   
[Kaggle **advanced** tutorial on SQL](https://www.kaggle.com/learn/advanced-sql)     

### Packages and Dependencies
R:   
```pacman``` - package that unpacks multiple packages at a time in R \
```DBI``` - package that allows users to access SQL databases \
```odbc``` - package that allows us to read SQL data into an R variable    
