# Exploratory Data Analysis on Students Performance in Exams.

## Overview
Exploratory Data Analysis of the exams conducted on students. this exams contain scores of three subjects `maths`,`reading` and `writing`.
<br>
In this data there is 1000 observations containg 8 variables other 2 added on data preprocessing.
<br>
## Aim of this EDA
In this EDA genreal Aim is to analyse the data in sequence manner and extract some specific question regarding the performance of the students.
<br>
Following question has been answered in this EDA.
* [Average marks of a student in all 3 subjects.](#avg)
* [Which student got the highest marks in total?](#high)
* [which student got the lowest marks in total?](#low)
* [What is the average score of students in each subjects?](#sub)
* [Ratio of Male and Female students.](#ratio)
* [Ratio of ethnicity of students.](#eth)
* [On an average which group performed the best in total marks?](#grp)
* [Which gender perfomed better overall?](#over)
* [Which gender performed better in each group?](#grp2)
* [How many students have failed and which group have the most?](#fail)
* [Students got more marks than others whose parents have higer education degree?](#par)
* [Those students whose completed their course got more grades in compare to those student who didn't?](#course)
* [Is there any correlation between the subjects?](#corr)
## Hypothesis Testing
* [Does all three subjects came from the same population data?](#hy1)
* [Does Male and Female comes form same population in terms of total scores?](#hy2)
---


### Average marks of a student in all 3 subjects.<a class="anchor" id="avg"></a>
![1](https://user-images.githubusercontent.com/90683408/145673620-d321b745-8238-476a-b9d0-43477b51d69f.png)
<br>
- As we can see the mean is 203 and median is 205 which is quite close.
![2](https://user-images.githubusercontent.com/90683408/145673645-7ff24a1d-2b7f-43a0-bc37-a5154195c0c6.png)
- By looking at the above histogram we can se the graph is normal, there is very slight left skew becuase one student got 27 marks in total. Therefore anslwet to to question : 
- **Average marks of students in all 3 subjects combined is around 205.**

### Which student got the highest marks in total?<a class="anchor" id="high"></a>
![3](https://user-images.githubusercontent.com/90683408/145673811-25491439-e368-4574-ae05-430b0f61dae1.png)
- As we can see 3 students from 1 male and 2 females from group E scored the maximum number of marks 300/300.

### which student got the lowest marks in total?<a class="anchor" id="low"></a>
![4](https://user-images.githubusercontent.com/90683408/145673849-c0115524-faea-48e4-832c-050e281e7383.png)
- One female from group C scored the least of total marks which is 27 out of 300.

### What is the average score of students in each subjects?<a class="anchor" id="sub"></a>
![5](https://user-images.githubusercontent.com/90683408/145673917-9f39705b-2b27-4711-9e41-e9ed2de767df.png)
<br>
![6](https://user-images.githubusercontent.com/90683408/145673950-e21ac110-addd-4ac0-a76b-57f29eee01e2.png)
- As we can see the reading and writing score mean ad median are quite similar, having mean of 69 for reading and 68 for writing and For median reading got 70 and writing 69. In the math scores both mean and median are bit low in comparison to other 2 subjects, having 66 for both mean and median.

### Ratio of Male and Female students.<a class="anchor" id="ratio"></a>
![8](https://user-images.githubusercontent.com/90683408/145674096-c4b4bbba-e6df-4fbd-97c6-0f1b8e353377.png)
<br>
![7](https://user-images.githubusercontent.com/90683408/145674069-222edad4-ba77-4548-9f10-7a16ca7e2f84.png)
- females are 518 and males are 482.

### Ratio of ethnicity of students.<a class="anchor" id="eth"></a>
![9](https://user-images.githubusercontent.com/90683408/145674157-fd410bc6-331d-402e-b796-efc0cb777cb4.png)
- From group C there are maximum number of students which is 319 followed by group D containg 262.
![10](https://user-images.githubusercontent.com/90683408/145674195-0ab90a1f-3578-4ee7-b26e-1bd5b413fc8a.png)

### On an average which group performed the best in total marks?<a class="anchor" id="grp"></a>
![12](https://user-images.githubusercontent.com/90683408/145674404-09dd9768-0bc7-4daa-b17b-2ce3c5a54157.png)
- From the above bar plot we can see that students from ethnicity 'group E' performed better in comparison to ther ethnicity groups.

### Which gender perfomed better overall?<a class="anchor" id="over"></a>
![13](https://user-images.githubusercontent.com/90683408/145674447-f600c6a6-4ade-4d04-88a8-7a8830b1f4e6.png)
- From the above bar plot we can conclude that the on average 'female' perfomed better in overall score in comparison to males

### Which gender performed better in each group?<a class="anchor" id="grp2"></a>
![15](https://user-images.githubusercontent.com/90683408/145675700-fa37d809-e604-42e5-a706-867aca53cf6a.png)
<br>
![14](https://user-images.githubusercontent.com/90683408/145675704-0d111e16-4e9c-42de-a293-fbe20f0c2910.png)
- From the above bar plot we can see in all group females perfomed better incomparison to males.

### How many students have failed and which group have the most?<a class="anchor" id="fail"></a>
![16](https://user-images.githubusercontent.com/90683408/145676757-a1eb0d57-7d5c-4117-b17c-01f1abbb3a93.png)
- Total failed student are 9 and group B got the most with the number of 5.

### students got more marks than others whose parents have higer education degree?<a class="anchor" id="par"></a>
![17](https://user-images.githubusercontent.com/90683408/145676925-2c60057e-13a2-4a7a-80c7-27897d7a7296.png)
From the above box plot we can see that those parent have master's degree their children got more grades in comparison to others. Therefore we can assume that if the parent is mroe educated then the student also tends to get better score.

### Those students whose completed their course got more grades in compare to those student who didn't?<a class="anchor" id="course"></a>
- First lets see how many students have completed the course?
- ![18](https://user-images.githubusercontent.com/90683408/145677027-ba4b204e-2741-457c-a4e8-5139dbf50ab6.png)
- ![19](https://user-images.githubusercontent.com/90683408/145677035-e3c4b1aa-0efa-41bf-8697-06618642cd22.png)
- There is 642 students who have not complted the course and 358 who have completed which makes 64 to 36 ratio between them.
- The mean and the median difference between these two is 22 and 24.
- Now, lets compare side by side boxplot.
- ![20](https://user-images.githubusercontent.com/90683408/145677112-a9773c05-dba1-4383-a62f-5191cfa58644.png)
- From the above box plot comparison we can see that those students who've completed the the couse got more total marks.
![21](https://user-images.githubusercontent.com/90683408/145677172-125d39ad-ab36-4044-931b-1c6165f7b11a.png)
By looking at the above histogram though the number of students who have not complated the couse is more but those students completed the course got more marks. Therefore, answer to the question : **Yes, those students whose completed their course got more grades in comparison to others who didn't.**

### Is there any correlation between the subjects?<a class="anchor" id="corr"></a>
- Math and reading score correlation is 0.8175796636720541
- Math and writing score correlation is 0.8026420459498083
- Reading and writing score correlation is 0.9545980771462479
![22](https://user-images.githubusercontent.com/90683408/145677340-2db96875-4847-4348-97af-be5d2d34c39d.png)
- As we can see all subjects are higly corelated with each other but among these three reading and writing score are higly correlated in comparison to maths to others. 

## Hypothesis Testing
### Does all three subjects came from the same population data?<a class="anchor" id="hy1"></a>

- ANOVA TESTING

H0 = all subjects are equal and comes from same population data.
<br>
H1 = all subjects are not equal and comes from different pupulation data.
<br>
pval :
<br>
<img src=https://user-images.githubusercontent.com/90683408/147758011-c5051d32-15f2-455a-b908-91f75dbad76b.png />

As we can see the pvalue the way to less than 0.05 that means one or more data come from different popluation. to find out which popupulation data is different we have to run turkey test.

- Turkey Range test.

<img src=https://user-images.githubusercontent.com/90683408/147758130-0bf5c9b5-a3d9-451d-828b-b24713c7f4e5.png />
From the turkey test we can see that math score are relatively different from reading and writing scores.


### Does Male and Female comes form same population in terms of total scores?<a class="anchor" id="hy2"></a>
- Two sample T-test

<img src=https://user-images.githubusercontent.com/90683408/147758210-4ae178d5-3c17-4713-8e07-9bd48150c4d2.png />
As we can see the pvalue is way less than 0.05 therefore we can reject the null hypothesis with 95% certainty that male and feamle total scores do not come from the same population data.
<br>

### Data source
- [kaggle](https://www.kaggle.com/spscientist/students-performance-in-exams)
