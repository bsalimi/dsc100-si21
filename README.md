![The_Data_Lifecycle](fig/The_Data_Lifecycle.jpg)

#   DSC 100: Introduction to Data Management



## Description:

Databases are at the heart of modern commercial application development. Their use extends beyond this to many other environments and domains where large amounts of data must be stored for efficient update, retrieval, and analysis. The purpose of this course is to provide a comprehensive introduction to the use of management systems for applications. Some topics covered are the following: data models, query languages, transactions, database design and database as a service.



## Instructional team:

**Instructor:**

[Babak Salimi](https://bsalimi.github.io/), bsalimi@ucsd.edu

**Course Assistants:**

Athavale, Shivani Sandeep, [ssathava@ucsd.edu](mailto:ssathava@ucsd.edu) 

Yeswanth Guntupalli, [yguntupa@eng.ucsd.edu](mailto:yguntupa@eng.ucsd.edu) 

Patil, Chaitanya Sharadchandra, [cpatil@ucsd.edu](mailto:cpatil@ucsd.edu)

**Lectures**:

The lecture for this class will be ASYNCHRONOUS and discussion sections will be SYNCHRONOUS. 

**Discussion:**: 

Wednesdays 4:00 pm to 4:50 pm 

**Office Hours:**

Mondays 4:00 PM to 5:00 PM (Babak Salimi)

**Zoom Meetings:** 

Links to the Zoom meetings will appear on the course's Canvas page.



**Piazza:** [DSC 100-wi21](https://piazza.com/ucsd/winter2021/dsc100) (Requires access code posted on Canvas)

**Have questions? Please email both Babak Salimi (bsalimi@ucsd.edu) and one of the TAs for questions on logistics. All other questions SHOULD be discussed on Piazza.**



## **Calender:**

**(subject to change)**

| Week |           Description           | Discussions | **Assignments / Remarks** | Lectures | **Optional Reading** |
| :--: | :-----------------------------: | :----: | ----- | --------------- | ---- |
|  1   | Intro, Data models, SQL | Sqlite practice [Source](https://drive.google.com/file/d/1hPmCCTVhdDo1vJKnZsJIR04oaWLwvbVw/view?usp=sharing), [Recording](https://drive.google.com/file/d/1UU-plebIEwNFsObNg-EciBBpzcvn9PE_/view?usp=sharing) |       | [Slides and recordings](./Lectures/lec01.md) | Sec. 2.1, 2.2, 2.3 |
|  2   |   Join and Aggregates in SQL    | SQL practice [Source](https://drive.google.com/file/d/1nr6QRDsr6f6RTWZsn80_slw4h6B3wTTh/view?usp=sharing), [Recording](https://drive.google.com/file/d/11RqJk7MJBxEjcF_kgNONM5NC06p88u0O/view?usp=sharing) | WQ1 due: Introduction, Data Models, and Simple SQL  <br />HW1 due: Sqlite | [Slides and recordings](./Lectures/lec02.md) | Sec. 6.1, 6.2 |
|  3   | Advanced SQL | Azure and Advanced SQL practice [Source](https://drive.google.com/file/d/1-q4rX9t1Oj9e-fInjzy3m6_xPQFn66LR/view?usp=sharing), [Recording](https://drive.google.com/file/d/1iQbXkLfl46LFkTnHZQObO-_MVinCDh2M/view?usp=sharing) | HW2 due: Basic SQL <br />WQ2 due: SQL Aggregates | [Slides and recordings](./Lectures/lec03.md) |  |
|  4   |  Relational Algebra  | Relational Algebra practice [Source](https://drive.google.com/file/d/1Z_vs0hlqfDnGYgZ_seTuJkZhI7456KjI/view?usp=sharing), [Recording](https://drive.google.com/file/d/1Pw_GA5SYiEDa-L-OGcpHows4izmIHL1M/view?usp=sharing) | WQ3 due: Nested Queries and Relational Algebra | [Slides and recordings](./Lectures/lec04.md) |  |
| 5  |        Query Evaluation <br />  **Mid-term**        | Exam practice [Recording](https://ucsd.zoom.us/rec/share/PYh0sN8DWfIEQnvnnpTtLDRLH04iqScNWk3Vsj_nRCcOeI2qlFm58fGRfmuPJDez.FHa-NhB1fpui6EJc) |  | [Slides and recordings](./Lectures/lec05.md) |  |
|  6   | Basics of Data Storage and Indexes | Midterm solutions [Recording](https://drive.google.com/file/d/1WvG_n7DSc5s8KEYvJBgClSyePGtE2O1T/view?usp=sharing) | HW3 due: Advanced SQL | [Slides and recordings](./Lectures/lec06.md) |  |
|  7   |         Cost Estimation <br /> NoSQL Databases         | Indexes and Cost Estimation [Source](https://docs.google.com/document/d/1QuVwn00LeX-4E4oRlV2mb5YjeUqvPV9WNKAAraQHiTY/edit?usp=sharing) [Recording](https://drive.google.com/file/d/1T3z42aQHAV5Ki0vrWmDAECyvlyyTps6_/view?usp=sharing) |  | [Slides and recordings](./Lectures/lec07.md) |  |
|  8   | Conceptual Design | Design practice [Source](https://drive.google.com/file/d/1ocF-qNILFQxcO8TYlTysBqkUToaGmoJu/view?usp=sharing) [Recording](https://drive.google.com/file/d/1Abq-DQrdbXwBpsE-b06PYFgMm_vIz9YL/view?usp=sharing) |  | [Slides and recordings](./Lectures/lec08.md) | Sec. 4.1, 4.6 |
|  9  | BCNF, Transactions | Transactions practice | WQ4 due: Conceptual Design <br />HW4 due: Conceptual Design | [Slides and recordings](./Lectures/lec09.md) |  |
| 10 | Transactions | Exam practice, | WQ5 due: Transaction Management |  |  |



## Workload:

**(subject to change)**

**Homework (45%):** There will be **weekly homeworks**. They will be based on the last 1-2 lectures. They are of two types:

1. **Written problem-solving and programming assignments (35%):**
   Start early and allocate enough time to solve these problems! 

2. **Gradiance exercises (10%):**
   [Gradiance](https://www.gradiance.com/) is an online service pioneered by one of the authors of the textbook, Prof. Jeffrey Ullman at Stanford. One of the best features of Gradiance is that you are permitted to test yourself on a particular topic as many times as you like. You receive immediate feedback for each attempt, which avoids the shortcoming of the traditional submit-and-then-wait-for-grades assignments where one error in understanding can permeate solutions to multiple problems and does not get rectified until much later. We encourage you to continue testing on each topic until you complete the part of the assignment with a 100% score. The highest score will be recorded. The questions will be the same in every attempt, but the answer choices will be selected at random. We will drop the lowest two scores at the end.

3. **Midterm (20%)** and **final  (35%)**: Details would be posted later.

4. **Extra Credit**: 

   - Some howmeworks have extra credit questions.

   - Large number of good answers on Piazza.  

## Resources / Communication / Toolkits:

**Book:** Although a textbook is not required in the course, the following textbook is optional and recommended. Lecture slides and recorded videos would be sufficient for this class.

Database Systems: The Complete Book, by Hector Garcia-Molina, Jeffrey D. Ullman, and Jennifer Widom. 2nd Edition. Prentice Hall. 2008.

**Canvas:** All weekly homework assignments should be turned in via Canvas.

**Gradescope:** We will use Gradescope for submission and grading of exams.

**Communication and Piazza:**  All important announcements will be sent through both Piazza and Canvas.

All questions that may be of general interest to the class should be directed to Piazza. You will get your questions answered faster on Piazza than via personal emails to the instructional team, because Piazza is monitored closely by everybody in the class, not just the course staff. You are highly encouraged to answer each others' questions on Piazza (*you will get extra credit for # of good answers on Piazza!*) and the instructional team would endorse/add to those answers.



## Related Groups:

- [UCSD Database Group](https://dbucsd.github.io/)

- [SIGMOD (Special Interest Group on Management of Data)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2F&sa=D&sntz=1&usg=AFQjCNEv9sM8CpuOZ7oxWFX_20353W6NZw)

- [VLDB (Very Large Data Base Endowment Inc.)](https://www.google.com/url?q=https%3A%2F%2Fwww.vldb.org%2F&sa=D&sntz=1&usg=AFQjCNEN7a3TJIOhpq3OC7bw9DKWHhki-w)

- [PODS (Symposium on Principles of Database Systems)](https://www.google.com/url?q=https%3A%2F%2Fsigmod.org%2Fpods%2F&sa=D&sntz=1&usg=AFQjCNEy52V8Padws9vrgz2GoFYinNgG9Q)

- [ICDT(IEEE International Conference on Data Engineering)](http://ieee-icde.org/)

- [CIDR (Conference on Innovative Data Systems Research)](http://www.google.com/url?q=http%3A%2F%2Fcidrdb.org%2F&sa=D&sntz=1&usg=AFQjCNHZ5MTU545Lei9xcYfQR9fHHLan5w)
