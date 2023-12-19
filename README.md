
:warning: 
**The first lecture starts at 8:45 AM, Feb 19, 2024.**
**I am still developing the course content. The content will be only be finalized by the end of the first week of the semester.**

<!-- vscode-markdown-toc -->
- [1. Important links](#1-important-links)
- [2. Course description](#2-course-description)
- [3. Learning objectivs](#3-learning-objectivs)
- [4. Course team](#4-course-team)
- [5. :dart: Grading policy](#5-dart-grading-policy)
	- [5.1. Homework](#51-homework)
	- [5.2. Group projects](#52-group-projects)
- [6. Detailed schedule](#6-detailed-schedule)

<!-- vscode-markdown-toc-config
	numbering=true
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc --><!-- vscode-markdown-toc -->


# DDL <!-- omit in toc -->

This repository contains the materials of the **MSc on Distributed Deep Learning Systems** course running in Spring 2024 at UniNE.


##  1. Important links

- [Project description](project.md)
- [Lab and assigment](homework.md)


##  2. Course description


Machine learning systems are often conventionally designed for centralized processing in that they first collect data from distributed sources and then execute algorithms on a single server. Due to the limited scalability of processing large amount of data and the long latency delay, there is a strong demand for a paradigm shift to distributed or decentralized ML systems which execute ML algorithms on multiple and in some cases even geographically dispersed nodes.

The aim of this  course is to let students learn how to design and build distributed ML systems via paper reading, presentation, and discussion; We provide a broad overview on the design of the state-of-the-art distributed ML systems, with a strong focus on the scalability, resource efficiency, data requirements, and robustness of the solutions. We will present an array of methodologies and techniques that can efficiently scale ML analysis to a large number of distributed nodes against all operation conditions, e.g., system failures and malicious attacks. The specific course topics are listed below.

The course materials will be based on a mixture of classic and recently published papers. 


<<<<<<< HEAD
##  3. <a name='Objective'></a>Learning objectivs
- To understand design principles of distribtued and federated learning systems
- To analyze distributed and federated ML in terms of the scalability and accuracy-performance tradeoff 
- To understand and impliment horizontal and vertical federated learning systems
- To understand and impliment federated learn systems on different  models, e.g., classification and generative models
- To understand and analyze volunerabilities and threat to federated learning systems, e.g., data poison attacks and freerider attacks
- To design and impliment defense strategies against adversarial clients in federated systems


##  4. Course team

This course will be mainly taught by [Prof. Lydia Y Chen](https://lydiaychen.github.io/).
TAs are Abel Malan and Aditya Shankar, who will run the lab and grade homework.

Lydia is the responsible instructor of this course and can be reached at **lydiaychen@ieee.org**.


##  5. :dart: Grading policy

This course has no final exam, instead the grade is largely determined through three components: 

1. Lab assigbment (30%): 3 individual lab assigment, due in week 4, 8, 12. 

2. Group project (70%): group project report (60%) and presentation (10%). The goal is to reproduce a paper and propose an algorithm to extend the paper. There will be an initial proposal in week 5, interim discussion with each team in week 9. The final report will be due in week 13, and 20 minutes presentation in week 14 as well.
   


**All assessment items (homework, and projects reports) have to be submitted via ILIAS.**


###  5.1. Homework
- Homework 1: due in week 4 
- Homework 2: due in week 8
- Homework 3: due in week 12

Students are given additional 48 hours grace period for late submission and will not receive any grade penalty. However, submissions after 48 hours grace period will not be considered and students will loose 15 points of their final grade. 


###  5.2. Group projects
<!-- 7 predefined project topics: evaluating the systems of 
-->
The objective is to reproduce and improve the performance of a paper from the course list (see project.md). The students need to hand in a final project report in the style of a short scientific paper, stating their individual contribution to the overall system performance. There are four milestones associated with this project (see project.md).

- Group size: 1-2 students
- Schedule: initial proposal (week 5), interim meeting (week 9), report due (week 134), and presentation/interview (week 14). 

[UPDATE] We change the requirement. For the final project, you just need to submit ppt slides, which summarize the results. If you submit a report, you will be getting bosnus point.

At the end of each project phase we will conduct a short interview (20 minutes per group) about the group project and its connection to the course content. Based on the project report and the interview, each member of the group receives a grade. 





##  6. Detailed schedule


**Week**|**Lecture Topic**|**Lab Topic**| **Assigment Due**
:-----|:-----|:-----|:-----
Week 1 (Feb 19) | Distributed Machine Learning I |No Lab |
Week 2 (Feb 26)| Memory and Aceeleration Technology | Dist SGD|
Week 3 (Mar 4) | Federated Learning I (Horizontal)| Fed AVG
Week 4  (Mar 11) | Federated Learning II (Vertical) | HW1 | HW1
Week 5 (Mar 18) | Hyper-parameter Tuning | Review of HW1| Project proposal
Week 6 (Mar 25) | Heterogneous and Multi-modality FL | VFL-I
Week 7 (April 1 )| Federated Generative AI | VFL-II
Week 8 (April 8)| Distributed inference | HW2 | HW2
Week 9 (April 15) |   Robust Distributed Learning | Review of HW2| Project midterm
Week 10 (April 22 )| Advanced Attacks and Defenses in Federated Learning  | Attacks
Week 11 (April 29)| Privacy Enhancing Technology for Federated Learning | Defenses
Week 12 (May 6)| Self-study | HW 3 | HW3
Week 13 (May 13)| Project prep with TA| Project prep with TA
Week 14 (May 20) | Project presentation| No Lab | Project report


