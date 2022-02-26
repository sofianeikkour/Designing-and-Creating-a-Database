# Designing-and-Creating-a-Database
---
Sofiane Ikkour
---
**Context and objective:**  
In this project, we will work with data related to [Major League Baseball](https://en.wikipedia.org/wiki/Major_League_Baseball) compiled by [Retrosheet](https://www.retrosheet.org/). Retrosheet is non-profit organization that's gathered game statistics from the 1800s to today. The goal is to convert and normalize this data into several separate tables using SQL and create a robust database of the game statistics.

**Dataset:**  
The main file we will work with is game_log.csv, which has been compiled and pre-cleaned from 127 separate CSV files from Retrosheet. In addition to the main file, we will work with three helper files also provided by Retrosheet. Those files are:
- park_codes.csv.  
- person_codes.csv.  
- team_codes.csv.  
- appearance_type.csv.  

**Note:** This code was written on RStudio.  
**Programming language:** SQL & R.  
**Packages:** readr, RSQLite, DBI, do.
