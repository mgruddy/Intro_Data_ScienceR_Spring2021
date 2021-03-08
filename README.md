# BSDS 100: Introduction to Data Science with R
The repository associated with BSDS100 at University of San Francisco in Spring 2021.

**Instructor:** Michael Ruddy

**Email**: mruddy@usfca.edu

**Class Time**: MWF, 10:35 - 11:35 AM Pacific

**Location:** Zoom (see Canvas)

**Office Hours**: TBD

**Book**: [R for Data Science](http://r4ds.had.co.nz/index.html) by Hadley Wickham and Garret Grolemund

**Syllabus**: [Link](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/BSDS100_Spring21_Syllabus.pdf)

## Course Learning Outcomes

By the end of this course, you will be able to

- Proficiently wrangle, manipulate, and explore data using the R programming language
- Utilize contemporary R libraries including *ggplot2*, *tibble*, *tidyr*, *dplyr*, *knitr*, and *stringr*
- Visualize, present, and communicate trends in a variety of data types
- Communicate results using Jupyter Notebook

## Course Overview

### Assessment

The course will be graded based on the following components:

- **Participation** (10%): You are expected to attend class when possible, participate in the Canvas forum, and work in groups for Case Studies assignments and the Final Project. You are also expect to follow the Code of Conduct (below).
- **Assignments** (50%): You will be assigned a computational assignment to be submitted with Jupyter Notebook regularly throughout the course.
- **Case Studies** (20%): You will be assigned applied case studies throughout the class that are to be completed as a group.
- **Final Project** (20%): The final project will be a computational case study that brings together the techniques learned throughout the semester. The description for this project will be provided towards the mid point of the semester.

### Code of Conduct

As students will often be asked to share and discuss their work, and work on assignments with their peers, the code of conduct **MUST** be followed. Students are expected to be highly respectful of their peers during and outside of class to help foster an inclusive environment where everyone is comfortable making mistakes and contributing. When working as a group, it is every group member's responsibility to make sure everyone has input and understands the answers given.

### Recorded Lectures

Recorded lectures are available to enrolled students. If you are unable to attend the live lecture, you must submit a Lecture Reflection Form (found [here](https://docs.google.com/forms/d/e/1FAIpQLSeJCWoDAdso9OJbMcQ7jRC3QZvakFfqTIBBxaW-DUqd4kNXWA/viewform?usp=sf_link)) to receive participation credit.


## Schedule

**Week 1**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | 1/25: [Introduction to Data Science and this course](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Slides/1_25Lecture.pdf)| [What is Data Science?](https://www.oreilly.com/library/view/doing-data-science/9781449363871/ch01.html)| [HW1](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW1.pdf) | 1/29| |
 | 1/27: [Using R in Jupyter Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Slides/Jan27Slides_Getting_Started.pdf) |[R for Jupyter Notebook](https://docs.anaconda.com/anaconda/navigator/tutorials/r-lang/)|Install software| 1/29| [Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Jan27Notebook_Getting_Started.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Jan27Notebook_Getting_Started.pdf)|
 | 1/29: R Basics| [Chapter 4: Basics](https://r4ds.had.co.nz/workflow-basics.html)|[HW2](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW2.pdf)|2/5|[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Jan29Notebook_R_Basics.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Jan29Notebook_R_Basics.pdf)|
 
 **Week 2**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
 | 2/1: [Data visualization & ggplot2](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Slides/Feb1Slides_DV1.pdf) | [Section 3.1 - 3.4](https://r4ds.had.co.nz/data-visualisation.html#introduction-1)| [HW3](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW3.pdf)| 2/5 | [Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb1Notebook_DV1.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb1Notebook_DV1.pdf)|
 | 2/3: More plotting! | [Section 3.5, 3.6](https://r4ds.had.co.nz/data-visualisation.html#facets) | | |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb3Notebook_more_ggplot.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb3Notebook_more_ggplot.pdf)|
 | 2/5: Graphics grammar & more | [Section 3.7 - 3.10](https://r4ds.had.co.nz/data-visualisation.html#statistical-transformations) | [HW4](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW3.pdf) | 2/12 |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb5Notebook_even_more_ggplot.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb5Notebook_even_more_ggplot.pdf)|
 
 
 **Week 3**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 2/8: Subsetting data | [Sections 5.1, 5.2, 5.4](https://r4ds.had.co.nz/transform.html#transform)|  |  | [Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb8Notebook_subsetting_data.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb8Notebook_subsetting_data.pdf)|
| 2/10: Data Transformation with dplyr I | [Sections 5.3, 5.5](https://r4ds.had.co.nz/transform.html#arrange-rows-with-arrange)| | | [Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb10Notebook_more_data_transformation.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb10Notebook_more_data_transformation.pdf)|
| 2/12: Data Transformation with dplyr II | [Section 5.6, 5.7](https://r4ds.had.co.nz/transform.html#grouped-summaries-with-summarise)| [HW5](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW5.pdf) | 2/19| [Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb12Notebook_summaries_and_grouping.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb12Notebook_summaries_and_grouping.pdf)|

**Week 4**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| No Class | | | | |
| 2/17: [Exploratory Data Analysis I](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Slides/Feb17Slides_EDA.pdf) | [Chapter 7](https://r4ds.had.co.nz/exploratory-data-analysis.html)| | | |
| 2/19: Explorartory Data Analysis II | [Chapter 7](https://r4ds.had.co.nz/exploratory-data-analysis.html)| | |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb19Notebook_import_explore.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/Feb19Notebook_import_explore.pdf)|

**Week 5**

Case Study Option 1 (Pokemon Dataset): [Assignment](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/CaseStudy1_P.pdf), [Data](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Data/pokemon_cleaned.csv)

Case Study Option 2 (NYC AirBnB 2019 Dataset): [Assignment](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/CaseStudy1_H.pdf), [Data](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Data/AB_NYC_2019.csv)

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 2/22: Case Study #1 in-class group-work | | | | |
| 2/24: Case Study #1 lab | | | | |
| 2/26: Case Study #1 presentations | | | | |

**Week 6**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 3/1: Data Structures I | [Sections 20.1 - 20.3](https://r4ds.had.co.nz/vectors.html)| | |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March1Notebook_Data_Structures_I.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March1Notebook_Data_Structures_I.pdf)|
| 3/3: Data Structures II | [Sections 20.4 - 20.5](https://r4ds.had.co.nz/vectors.html#using-atomic-vectors)| | |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March3Notebook_Data_Structures_II.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March3Notebook_Data_Structures_II.pdf)|
| 3/5: Data Structures III | [Sections 20.6, 20.7](https://r4ds.had.co.nz/vectors.html#attributes), [Ch 10](https://r4ds.had.co.nz/tibbles.html) | | |[Notebook](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March5Notebook_Data_Structures_III.ipynb), [pdf](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Notebooks/March5Notebook_Data_Structures_III.pdf)|

**Week 7**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 3/8: Data Import/Export | [Chapter 11](https://r4ds.had.co.nz/data-import.html)| [HW6](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW6.pdf) | 3/12 | |
| 3/10: Tidy Data I | [Sections 12.1 - 12.3](https://r4ds.had.co.nz/tidy-data.html#introduction-6)| | | |
| 3/12: Tiday Data II | [Sections 12.4 - 12.5](https://r4ds.had.co.nz/tidy-data.html#separating-and-uniting) | [HW7](https://github.com/mgruddy/Intro_Data_ScienceR_Spring2021/blob/main/Assignments/HW7.pdf) | 3/26 | | 
 
 **Week 8**
 
 Spring Break!
 
 **Week 9**
 
 | Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 3/22: Relational Data I | | | | |
| 3/24: Relational Data II | | | | |
| 3/26: Factors & Dates I | | | | |

**Week 10**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 3/29: Factors & Dates II | | | | |
| 3/31: Missing Values and Imputation | | | | |
| 4/2: No Class | | | | |

**Week 11**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 2/5: Case Study #2 in-class group-work | | | | |
| 2/7: Case Study #2 lab | | | | |
| 2/9: Case Study #2 presentations | | | | |

**Week 12**

| Topic | Reading | Assignment | Due Date | In Class Code |
 | :---  | :---:  | :---:  | :---:  | :---: |
| 2/5: Functional Programming I | | | | |
| 2/7: Functional Programming II | | | | |
| 2/9: Functional Programming III | | | | |
 
 ### Important USF Dates
 
 - Monday, January 25th: First day of classes
 - Friday, February 12th: Census Day (Last day to withdraw with tuition reversal)
 - Monday, February 15th: President's Day (no class)
 - Monday, March 15th - Friday, March 19th: Spring Break (no class)
 - Friday, April 2nd: Easter Holiday (no class)
 - Monday, April 12th: Last day to withdraw
 - Wednesday, May 12th: Last day of class
 
 ### Important Class Dates
 
 - Monday, February 22nd: In-class work on Case Study #1
 - Friday, February 25th: In-class present Case Study #1
 - Wednesday, March 31st: Form groups for Final Project w/ Broad Topic
 - Monday, April 5th: In-class work on Case Study #2
 - Friday, April 9th: In-class present Case Study #2
 - Wednesday, May 5th: Final Project Description due
 - Friday, May 7th: In-class work on Case Study #3
 - Wednesday, May 12th:  In-class present Case Study #3
 - Monday, May 17th, 10am-12: Final Exam date (Project Presentations)
 
 
 
 
