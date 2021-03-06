---
title: "PS811 Statistical Computing in Political Science"
author: "Devin Judge-Lord"
subtitle: "University of Wisconsin-Madison"
---

JudgeLord@wisc.edu | 715.204.4287

Fridays 9-10 AM Soc Sci 6125, Jan. 25 - May 3

*No class March 8 (visit day) or March 22 (spring break)

**Office hours:** Fridays 10-12 AM in the North Hall computer lab.

**Required software:** [R](https://www.rstudio.com/products/rstudio/download/#download), [LaTeX](https://www.latex-project.org/get/), [git](https://git-scm.com/downloads)

Materials will be on the course [website](https://github.com/judgelord/PS811).

Students should clone this repository: <https://github.com/judgelord/PS811>

- In RStudio: File -> New Project -> Version Control -> Git -> [paste URL]  <[Instructions](https://github.com/judgelord/PS811/blob/master/github_instructions.md)>

# \#goals
This course builds core research skills to aid coursework for other stats classes and research papers:

## No-brainers 
- Keeping data [tidy](http://garrettgman.github.io/tidying/)
- Writing readable code (e.g. [pipe](https://magrittr.tidyverse.org/articles/magrittr.html), don't nest)
- Writing efficient, easy-to-edit code (use functions, rarely copy & paste)
- Clearly presenting your data & results (tables, figures) 
- Never copy & paste tables or figures into a paper

---

## Worthwhile 
- Backing up / version control (e.g. [git](https://github.com/judgelord/PS811/3-git.html))
- Commenting your code 
- Being organized (e.g. project folders)
- Being portable (e.g. [`here`](https://github.com/jennybc/here_here))
- Breaking projects up into component parts

---

## Potential next steps
- Getting new data (e.g. web scraping & API's)
- Text analysis
- Classification 
- Dimension reduction
- Machine learning
- Duration modeling
- Surveys (e.g. qualtrics & mturk)
- Using remote servers

---

## Assignments

1. The first assignment is to write a problem set for a statistics class (e.g. 813) in a plain text notebook--- [R Markdown](http://rmarkdown.rstudio.com) or similar (e.g. [Jupyter](https://jupyter.org/)). (10%)


[Example Problem Set / Data Exercise](https://github.com/judgelord/PS811/raw/master/example_problem_set.pdf)

2. The remaining assignments are incremental steps in producing a reproducible analysis of a dataset you choose (50%)

[Example Portfolio](https://judgelord.github.io/PS811/example_portfolio.html)

All data files in your 811 project folder should be in a subfolder named "data" and all figures should be in a subfolder named "figs"---add `knitr::opts_chunk$set(fig.path=‘figs/‘)` to your `setup` chunk to make sure all figures are saved to this folder.

- Feb. 1: publish a draft portfolio page with your research interests and potential data source(s) 
- Feb. 15 - Load and summarize some aspect(s) of your chosen data on your portfolio page with either output from summarize() or a ggplot()
- March 1: Simple plot(s) of something interesting with ggplot
- March 15: In-class workshop on data viz. For each draft portfolio, the class will constructively suggest how your point may be better communicated, and we will learn how to make it happen
- May 3: 5-minute presentations of data analysis portfolio pages

Attendance: If you are solid on a week's topic and want to skip, this is fine, just show some work demonstrating this *ahead of time*. We may also use DataCamp tutorials to build or demonstrate skills as needed (i.e. according to your background knowledge and interests). (40%)


---

### 2. [R Markdown](https://judgelord.github.io/PS811/2-RMarkdown.html)

- Using [R Markdown](http://rmarkdown.rstudio.com)

- Class notes template
<[HTML](https://judgelord.github.io/PS811/example_notes.html)> 
<[PDF](https://github.com/judgelord/PS811/raw/master/example_notes.pdf)>

- [Problem set / Data exercise template](https://github.com/judgelord/PS811/raw/master/example_problem_set.pdf)


**Assignment 1:** Complete a problem set in R Markdown

---

### 3. [Project folders and git](https://judgelord.github.io/PS811/3-git.html)

- Project files (e.g. /data, /figs, /functions)
- File paths with `here`: [Ode to the here() package](https://github.com/jennybc/here_here) 

**Assignment 2:** Publish your 811 webpage/portfolio on [GitHub](http://GitHub.com): Your research interests + potential questions, data, & methods

### 4. [Tidy data + readable code](https://judgelord.github.io/PS811/4-tidy-data.html)

- Nameing things
- Manipulating data with [`dplyr`](https://dplyr.tidyverse.org/) (See this [cheatsheet](https://github.com/rstudio/cheatsheets/blob/master/data-transformation.pdf)) & getting the most out of other [`tidyverse`](https://www.tidyverse.org/learn/) tools
- New variables with `mutate()` and `ifelse()`
- Pipes with [`magrittr`](https://magrittr.tidyverse.org/articles/magrittr.html) (`%>%` and `%<>%`)
- Output (tables, [`ggplot`](https://github.com/rstudio/cheatsheets/blob/master/data-visualization-2.1.pdf?raw=1))
- Commenting (`# R comment`, `% LaTeX comment`, `<!-- markdown / html coment -->`)

**Assignment 3:** Choose a dataset, load and summarize some part of it on your portfolio page.  ***DUE: FEB 15**

---

### 5. Efficient code that does not break

- Saving and loading data files
- Reproducible tables and figures

**Assignment 4:** Save your data in a /data subfolder and add a `setup.R` script to your 811 git repository. Work on data summary, changing variable names and values to improve clarity. Use `here()` for all file paths.


---

### 6. [Summary analysis + data viz](https://judgelord.github.io/PS811/6-data-viz.html)

- Presenting model results 
- More `ggplot` --- choosing layers (lines, intervals, colors, labels, facets, maps)

**Assignment 5:** Finish up initial data summary: use ggplot to show something interesting or puzzling about your data. **DUE: MARCH 1**

Here is an [example portfolio](https://judgelord.github.io/PS811/1-intro-to-PS811.html) with a data summary that employs several of the tools we will have learned, including loading data, commenting code, renaming variables, making new variables, filtering data, building a custom function, pipes, adjusting figure size and labels, and a number of `ggplot` layers.

---

### Data viz workshop - MARCH 15


- Bonus (optional): convert your 811 web page to a slideshow with `xaringan` (When you have to make a conference presentation, you'll be glad you did!)

---

### 7. [Tidy text analysis](https://judgelord.github.io/PS811/7-tidy-text.html)

### 8-(n-1). TBD

--- 

### n. Final data analysis presentations - MAY 3

---




## More resources and thanks!

Awesome previous 811 instructors: [Mike DeCrescenzo](https://mikedecr.github.io/) (Mike's [811 lectures](https://mikedecr.github.io/811/)), [Hannah Chapman](https://hannahschapman.com/), [Sarah Bouchat](https://bouchat.github.io/) (Sarah's [lectures](https://bouchat.github.io/553)), Jack Edelson.

Similar courses by [Rochelle Terman](https://github.com/rochelleterman/PS239T), Rachel Bernhard, and [Jae Yeon Kim](https://github.com/jaeyk/PS239T).

[Karl Broman'slist of resources](https://github.com/kabagg/sisbid_2018_rr/blob/master/Resources/resources.md) for R Markdown, git, coding, etc.

Templates from Mike DeCrescenzo, Adam Lauretig, and Steven V. Miller. See [Mike's LaTeX workshop materials](https://mikedecr.github.io/code/)

---

## RULES, RIGHTS & RESPONSIBILITIES

•	See the Graduate Guide’s [Rules, Rights and Responsibilities](http://guide.wisc.edu/graduate/)

---

## ACADEMIC INTEGRITY

By enrolling in this course, each student assumes the responsibilities of an active participant in UW-Madison’s community of scholars in which everyone’s academic work and behavior are held to the highest academic integrity standards. Academic misconduct compromises the integrity of the university. Cheating, fabrication, plagiarism, unauthorized collaboration, and helping others commit these acts are examples of academic misconduct, which can result in disciplinary action. This includes but is not limited to failure on the assignment/course, disciplinary probation, or suspension. Substantial or repeated cases of misconduct will be forwarded to the Office of Student Conduct & Community Standards for additional review. For more information, refer to <http://studentconduct.wiscweb.wisc.edu/academic-integrity>

---

## ACCOMMODATIONS FOR STUDENTS WITH DISABILITIES

McBurney Disability Resource Center syllabus statement: “The University of Wisconsin-Madison supports the right of all enrolled students to a full and equal educational opportunity. The Americans with Disabilities Act (ADA), Wisconsin State Statute (36.12), and UW-Madison policy (Faculty Document 1071) require that students with disabilities be reasonably accommodated in instruction and campus life. Reasonable accommodations for students with disabilities is a shared faculty and student responsibility. Students are expected to inform faculty [me] of their need for instructional accommodations by the end of the third week of the semester, or as soon as possible after a disability has been incurred or recognized. Faculty [I], will work either directly with the student [you] or in coordination with the McBurney Center to identify and provide reasonable instructional accommodations. Disability information, including instructional accommodations as part of a student's educational record, is confidential and protected under FERPA.” <http://mcburney.wisc.edu/facstaffother/faculty/syllabus.php>

---

## DIVERSITY & INCLUSION

Institutional statement on diversity: “Diversity is a source of strength, creativity, and innovation for UW-Madison. We value the contributions of each person and respect the profound ways their identity, culture, background, experience, status, abilities, and opinion enrich the university community. We commit ourselves to the pursuit of excellence in teaching, research, outreach, and diversity as inextricably linked goals.

The University of Wisconsin-Madison fulfills its public mission by creating a welcoming and inclusive community for people from every background – people who as students, faculty, and staff serve Wisconsin and the world.” <https://diversity.wisc.edu/>
