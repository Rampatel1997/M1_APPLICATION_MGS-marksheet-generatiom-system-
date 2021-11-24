# M1_APPLICATION_MGS-marksheet-generatiom-system-

INTRODUCTION:>

Mark sheet generation will reduce the time to create the marks card of the student. The University only needs to upload the marks of student in each subject and then the system will complete rest of the work like calculating total marks, calculating percentage, giving grades and produce digital result. The computers are much faster than the human, and hence it will take less time to produce the result. The University management can also change the procedure to produce the result if they want. This application can also reduce the cost because it involves only person from user side to generate student marksheets.

Objective:>

Prediction of the final grade of Portugese high school students.

Problem Statement:>

The problem statement can be defined as follows ”Given a dataset containing attribute of 396 Portuguese students where using the features available from dataset and define classification algorithms to identify whether the student performs good in final grade exam, also to evaluate different machine learning models on the dataset.”

Description Of Dataset:>

This data approach student achievement in secondary education of two Portuguese schools.
The data attributes include student grades, demographic, social  and it was collected by using school reports and questionnaires.
Two datasets are provided regarding the performance in two distinct subjects: Mathematics (mat) and Portuguese language (por).
In  the two data sets were modeled under binary/five-level classification and regression tasks. 
Important note: the target attribute G3 has a strong correlation with attributes G2 and G1.
This occurs because G3 is the final year grade (issued at the 3rd period), while G1 and G2 correspond to the 1st and 2nd period grades.
It is more difficult to predict G3 without G2 and G1.

Attribute Information:

>school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
>sex - student's sex (binary: 'F' - female or 'M' - male)
>age - student's age (numeric: from 15 to 22)
>address - student's home address type (binary: 'U' - urban or 'R' - rural)
>famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
>Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
>Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
>Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 - “ 5th to 9th grade, 3 - “ secondary education or 4 - “ higher education)
>Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
>Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
>reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
>guardian - student's guardian (nominal: 'mother', 'father' or 'other')
>traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
>studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
>failures - number of past class failures (numeric: n if 1<=n<3, else 4)
>schoolsup - extra educational support (binary: yes or no)
>famsup - family educational support (binary: yes or no)
>paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
>activities - extra-curricular activities (binary: yes or no)
>nursery - attended nursery school (binary: yes or no)
>higher - wants to take higher education (binary: yes or no)
>internet - Internet access at home (binary: yes or no)
>romantic - with a romantic relationship (binary: yes or no)
>famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
>freetime - free time after school (numeric: from 1 - very low to 5 - very high)
>goout - going out with friends (numeric: from 1 - very low to 5 - very high)
>Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
>Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
>health - current health status (numeric: from 1 - very bad to 5 - very good)
>absences - number of school absences (numeric: from 0 to 93)

Methodology:>


Since universities are prestigious places of higher education, students’ retention in these universities is a matter of high concern.
It has been found that most of the students’ drop-out from the universities during their first year is due to lack of proper support in undergraduate courses.
Due to this reason, the first year of the undergraduate student is referred as a “make or break” year.
Without getting any support on the course domain and its complexity, it may demotivate a student and can be the cause to withdraw the course.

There is a great need to develop an appropriate solution to assist students retention at higher education institutions.
Early grade prediction is one of the solutions that have a tendency to monitor students’progress in the degree courses at the University and will lead to improving the students’ learning process based on predicted grades.

Using machine learning with Educational Data Mining can improve the learning process of students.
Different models can be developed to predict students’ grades in the enrolled courses, which provide valuable information to facilitate students’ retention in those courses. This information can be used to early identify students at-risk based on which a system can 1 suggest the instructors to provide special attention to those students.
This information can also help in predicting the students’ grades in different courses to monitor their performance in a better way that can enhance the students’ retention rate of the universities.

Using various packages such as cufflinks, seaborn & matplotlib to represent the data along with different attributes graphically or pictorially to analyse the dataset for predicting the Final Grade(G3).

Machine Learning Algorithms used:>


>Linear Regression
>
>ElasticNet Regression
>
>Random Forest
>
>Extra Trees
>
>SVM
>
>Gradient Boosted
>
>Baseline
>
>Experimental Results
>
>KDE Plot to view all attributes using cufflinks
>
>Box Plot to view all attributes using cufflinks
>
>Histogram Plot for G3 (Final Grade) using cufflinks
>
>Pictorial representation of any null data present in the dataset.
>
>Count Plot for Student Sex Attribute
>
>Kernel Density Estimation for Age of Students.
>
>Count PLot for Male & Female students in different age groups.
>
>Count Plot for students from Urban & Rural Region.
>
>Does age affect final grade
>
>Do urban students perform better than rural students?
>
>Previous Failures vs Final Grade(G3)
>
>Family Education vs Final Grade(G3

>Higher Education vs Final Grade(G3)
>
>Go Out vs Final Grade(G3)
>
>Reason vs Students Count
