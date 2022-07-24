# Pewlett-Hackard-Analysis

## *The Goal and Methodology*
### In this analysis we wanted to determine the impact of impending retirements on Pewlett-Hackard's workforce.

The things we wanted to know in particular are:
1. How many people were retiring?
    * What department are they in?
    * How many people with each title are retiring?
2. How many people are eligible for the mentorship program?
    * What departments are they in?

---
## *How many people are retiring?*
#### We queried our employee database to understand how many people would be retiring. We were specifically looking for the total number as well as what job titles would be most affected:

1. First we needed the total number of unique employees who were retiring
    * We found that **72,458** people were retiring across various titles
    * A snippet of the file file structure and the first few rows is included below for reference

![Unique Titles Summary](https://github.com/05Perseus/Pewlett-Hackard-Analysis/blob/main/Resources/unique_titles.png)

2. The next thing we needed was a summary of the retirees by title
    * We found that **25,916** Senior Engineers would be retiring!
    * **72%** of the retirees were in a Senior level position
    * This is a potentially great loss of intellectual capital

---
## *Who would be eligibly for a mentorship program?*
#### Instead of losing all that intellectual capital, the idea of a mentorship program for knowledge transfer came up. What we needed to know is who would be eligible for such a program?

1. In our query we used fitler criteria of 1965 birthdates to determine eligibility
2. This gave us approximately **1,549** employees who were eligible

---
## *Conclusion*
In conclusion, we are in big trouble. There is a significantly higher number of people leaving the company than people who are eligible for mentorship to the next level.

1. We found that **72,458** people were retiring across 7 different titles
    * This includes **2 Department Managers**
2. **72%** (or **50,842**) of the retirees were in a Senior level position which will be a huge hit
3. We only have **1,549** people eligible for mentorship, which means we don't have enough backfill

We need more data. In addition to what we've already learned it would be good to answer a few more questions:

4. How many more people would be eligible for mentorship if we expanded the age-range?
5. What are the title counts for our eligible up and comer employees?

With this extra information we would be better prepared to weather oncoming the retirement wave.
 
