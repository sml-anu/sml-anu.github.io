  ---
title: "COMP4670/8600 Statistical Machine Learning 2022"
description: "a broad but thorough intermediate level course of statistical machine learning, emphasising the mathematical, statistical, and computational aspects"
date: "2000-01-02"
categories:
  - "edu"
  - "courses"
  - "resources"
tags:
  - "cm"
---

<!--more-->
<a name="top"></a>

<nav>
<a href="/sml2022/#top">Top of the page</a> |
<a href="/sml2022/#schedule">Schedule</a> |
<a href="/sml2022/#staff">Staff</a> |
<a href="/sml2022/#book">Books</a> |
<a href="/sml2022/#sites">Sites</a> |
<a href="/sml2022/#assessments">Assessments</a> |
<a href="/sml2022/#enroll">Enrollling</a>
</nav>

### Overview

Statistical Machine Learning plays a key role in science and technology.
Some of the basic questions raised are:

* What is a good model for the available data?
* How can we fit the parameters of the model to the available data?
* How will a model perform on data which has yet to be observed?

This course provides a broad but thorough intermediate level study of the methods and practices of statistical machine learning, emphasising the mathematical, statistical, and computational aspects. Students will learn how to implement efficient machine learning algorithms on a computer based on principled mathematical foundations. Topics covered will include Bayesian inference and maximum likelihood modelling; regression, classification, density estimation, clustering, principal and independent component analysis; parametric, semi-parametric, and non-parametric models; basis functions, neural networks, kernel methods, and graphical models; deterministic and stochastic optimisation; overfitting, regularisation, and validation.

The course will use Python 3 and [Jupyter](https://jupyter.org/) notebook for all tutorials, and assignment/exam questions involving programming.
<!-- In particular, we will use the  which combines code, text, mathematics and plots into a single document. It will be provided on all computers used in the labs. -->

<a name="schedule"></a>
### Course Schedule
* [ANU Lecture and Lab Timetables](http://timetabling.anu.edu.au/sws2021/)
* [ANU Exam Timetables](https://exams.anu.edu.au/timetable)

<iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQB2-TzTy9CF7tGStSJv_Kq7Y7f1z9V14GU9cvhpCZ--0R8EWmM6qt3gp8jQHL1TQlMomk5blsrq9fK/pubhtml?gid=440828989&amp;single=true&amp;widget=true&amp;headers=false"
width=1000px height=500px>>
</iframe>

<a name="staff"></a>
## Course Staff

* Lecturer: [Lexing Xie](http://users.cecs.anu.edu.au/~xlx/index.html)

* Tutors:

|       |    |    |
| ----------- | ----------- |  ----------- |
|  ![alex](/img/people/alex-s-100.jpg) Alexander Soen <br />  | ![chamin](/img/sml-tutors/chamin_100.jpg) Chamin Hewa Koneputugodage       | ![shidi](/img/sml-tutors/shidi_100.png) Shidi Li  |
| ![tianyu](/img/sml-tutors/tianyu_100.jpg) Tianyu Wang        | ![josh](/img/people/josh_100.jpg) Josh Nguyen | ![minchao](/img/sml-tutors/minchao_100.png) Minchao Wu  |
| ![katya](/img/sml-tutors/katya_100.jpg) Ekaterina (Katya) Nikonova | ![ruiqi](/img/sml-tutors/ruiqi_100.jpg) Ruiqi Li | ![haiqing](/img/sml-tutors/haiqing_100.jpg) Haiqing Zhu |
| ![belona](/img/sml-tutors/belona_100.jpg) Belona Sonna  | ![dillon](/img/sml-tutors/dillon_100.jpg) Dillon Chen | ![rong](/img/sml-tutors/rong_100.jpg) Rong Wang |
| ![Barclay](/img/sml-tutors/barclay_100.jpg) Barclay Zhang  | ![evan](/img/sml-tutors/evan_100.jpg) Evan Markou | ![zhiyuan](/img/sml-tutors/zhiyuan_100.jpg) Zhiyuan Wu |


<a name="book"></a>
### Textbook

Required: **Christopher M. Bishop: Pattern Recognition and Machine, Springer, 2006** (selected parts), available [here](https://www.microsoft.com/en-us/research/people/cmbishop/prml-book/)

We also recommend:

* Deisenroth, Faisal, and Ong, [Mathematics for Machine Learning](https://mml-book.com/). Cambridge University Press.
* Moritz Hardt and Benjamin Recht, [Patterns, Predictions and Actions: A story about machine learning](https://mlstory.org/index.html)
* MacKay, [Information Theory, Inference, and Learning Algorithms](http://www.inference.org.uk/itila/book.html), Cambridge University Press
* Murphy, [Probabilistic Machine Learning: An Introduction](https://probml.github.io/pml-book/book1.html), MIT Press, 2021

<a name="sites"></a>
### Course sites

* Piazza will be used for all course discussions. <br/>
  Signup at http://piazza.com/anu.edu.au/spring2022/comp4670comp8600 with access code "logistic_regression"

* Microsoft teams (ANU edition) will be used to hold lectures and labs/tutorials each week.
  The link to SML-2021 Team is [here](https://teams.microsoft.com/l/team/19%3a4ryjpK6hSlyJTMdBt6R4PaMp-jMfxNc1Ksnih5QTnP41%40thread.tacv2/conversations?groupId=a4ee312b-f0eb-49e0-994b-534f9e11f537&tenantId=e37d725c-ab5c-4624-9ae5-f0533e486437), use code "87v89zy" to join.

* Gradescope will be used to manage assignment submissions and give feedback. <br/>
  * Register for Gradescope at http://gradescope.com using your ANU e-mail and include your student ID number with sign-up. Use the entry code 3YNNKW to sign up for this course.
  * A detailed guide about how to submit your assignemnt to Gradescope is here https://help.gradescope.com/article/ccbpppziu9-student-submit-work

* Wattle will be used to host the final exam.  

<a name="assessments"></a>
### Assessments

* Quiz 1, 2.5% (due week 4)
* Quiz 2, 2.5% (due week 8)
* Assignment 1, 20% (due Mon 12:00noon week 6, Canberra time)
* Assignment 2, 20% (due Mon 12:00noon week 11, Canberra time)
* Video assignment, 20% (due Tue 23:59 week 12, Canberra time)
* Final exam, 35% (online via wattle, during examination period)

<!-- + Practice assignment for using Gradescope to upload assignments, 0%, sometime in the first 5 weeks -->

#### Online quiz expectations

* Quiz will be conducted on wattle, and automatically graded. 
* Students can attempt the quiz once, with no time limit.
* Open book -- students are expected to complete the quiz by themselves, and are free to consult the textbook, notes, or relevant internet resources.
* The quiz will be redeemable with final exam, i.e. score for each quiz is calculated as _Qx' = max(Qx, Final)_, where _Qx_ is the raw quiz score for Quiz 1 (_Q1_) or Quiz 2 (_Q2_), out of 100. _Final_ is the score for the final exam, out of 100.
* There will be NO late period for either quiz. Special consideration requests will also NOT be accepted, due to the rapid feedback cycle and redeemable nature of the quizzes.

#### Paired assignment expectations

* Students can submit Assignment 1 and Assignment 2 in a self-formed team of size 1 or 2 people.
* Students submitting in a pair act as one unit:
  * Both of the two students should fully understand all the answers in their submission
  * Each student in the pair must understand the solution well enough in order to reconstruct it by him/herself
* In the case of team submission, the assignment should include a brief statement about who contributed what.
  * In most cases, students in the same team can expect to get the same mark for the team assignment

#### Video assignment

The video assignment is an individual assignment.

  * Each student are expected to upload a video talking about one topic from the assignments or labs, and the thinking behind it.
  * The length of the video should be between 4 to 8 minutes, with an under- and over- length penalty being 1 point per 10 seconds (or part thereof).
  * Grading scheme for the video assignment will be made available in advance of the due date.

#### Late policy
This policy applies to Assignment 1, Assignment 2, and the video assignment.

* Assignment submission that are late from 1 min to 24 hours attract a [5% penalty (of possible marks available)](https://policies.anu.edu.au/ppl/document/ANUP_004604).

* Submissions late by more than 24 hours will not be accepted.


<a name="enroll"></a>
### Enrolment questions

*To enrol in this course you must have completed the pre-requisites as per the [COMP4670](https://programsandcourses.anu.edu.au/2022/course/COMP4670) or [COMP8600](https://programsandcourses.anu.edu.au/2022/course/COMP8600) course description.*

The topics covered in this course have some overlap with a number of courses in the major for [Statistical Data Analytics](https://programsandcourses.anu.edu.au/major/STDA-MAJ). Please have a look at the first few tutorial sheets for an indication of the kinds of mathematics and statistics that we will build upon.

If ISIS does not let you enroll but you believe you should be able to (e.g. have taken equivalent courses as the pre-qreq in the different university), then submit a permission code application [here](https://cecs.anu.edu.au/current-students/policies-and-resources/enrolling-cecs-courses).
