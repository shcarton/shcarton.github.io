---
layout: page
title: CS759/859 Spring 2024
permalink: /cs759spring2024/
description: "CS759/859 - Natural Language Processing"
nav: false
# nav_order: 4
---
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-0pky{border-color:inherit;text-align:left;vertical-align:top}
</style>

## Class information


| Start Date | End Date | Days      | Time            | Location  |
|------------|----------|-----------|-----------------|-----------|
| 1/24/2022  | 5/4/2022 | Tue/Thurs | 3:40pm - 5:00pm | KING N101 |
{:.tg}


<br/>

**Office hours:** Wednesday 1 PM to 2 PM, location: Online (see MyCourses announcement for Zoom link)

**Prerequisites:** CS 515 (or equivalent) and MATH 539 or MATH 644

**Description:** This class covers natural language processing, including both methods and well-known applications. Methods discussed will range from classical probabilistic methods such as Naive Bayes and Hidden Markov Models, to contemporary neural network methods, including word vector models, recurrent neural networks, and Transformer-based models. Applications discussed will include text classification, machine translation, and conversation systems (among others).

## Syllabus


Updated: 2/20/2024

### Key information

**Syllabus subject to change**
This syllabus is subject to change. I will make an announcement when this happens, but it is on you as students to keep up. 

**Mandatory reporter**
I am a mandatory reporter. What this means is if I hear about a situation where a student is being or has been sexually harassed, assaulted, stalked, or otherwise endangered, I am legally obligated to file a report with the UNH DEI office. That said, I am more than happy to help students find guidance in dealing with these types of situations, subject to my reporting requirements.

### Course overview

This course is a special topics lecture on natural language processing for graduate students and advanced undergraduates. Every class session will consist of a lecture, with a weekly homework assignment due the following week. Homeworks will be distributed and completed in Python as Google Colab notebook, with the exact details of distribution and submission to follow. 

There will be a final exam in-class the week before the official finals week, precise date TBD. 

There will be a final project, chosen from a list of potential topics, with a milestone check-in, a final submission, and a mandatory poster session at the end of the semester. 

There is no required textbook, nor mandatory readings. 

### Grading distribution

The grading distribution is as follows:
<br/>65% - Homeworks
<br/>20% - Final project
<br/>10% - Final exam
<br/>5% - Attendance and classroom activities

### Late policy

Homeworks and project milestones can be turned in up to 5 days late, with a stacking 10% per-day penalty on the maximum possible grade, before receiving a zero. 

### Attendance policy
In-person attendance is encouraged and 5% of the final grade will be based on attendance and participation in discussion and classroom activities.

I am happy to accommodate life events. If you get COVID or have some other pressing reason to attend remotely, I can temporarily move the class to a hybrid format. I’m also happy to grant excused absences for medical or family problems, or various other kinds of emergencies. Let me know as early as possible if you need either of these kinds of accommodation. 

### Academic honesty policy

Students are welcome to ask for and give each other assistance on the homework assignments, but these assignments should be completed individually and your work should be your own. 

Given the specialized nature of the topic, it is unlikely that AI coding tools such as ChatGPT will be effective in completing the weekly homework assignments. But needless to say, the use of these kinds of tools is not allowed. 

Generally speaking, I will follow the [UNH academic honesty policy](https://catalog.unh.edu/graduate/academic-regulations-degree-requirements/academic-honesty/), which lays out what is considered cheating and what the process is for dealing with cases of reported academic dishonesty.

### Schedule

| Week 	 | Lecture 	 | Day 	 | Date 	  | Description                                	                       | Assignment Due 	      | Slides                                                                                                                    | Notebook                                                                                            |
|--------|-----------|-------|---------|--------------------------------------------------------------------|-----------------------|---------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| 1    	 | 1       	 | Tu  	 | 1/23 	  | Introduction to NLP                        	                       | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_1_intro_to_NLP.pdf)                  |                                                                                                     |
| 1    	 | 2       	 | Th  	 | 1/25 	  | Basics of linguistics                      	                       | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_2_overview_of_linguistics.pdf)       |                                                                                                     |
| 2    	 | 3       	 | Tu  	 | 1/30 	  | Representing text numerically              	                       | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_3_numerically_representing_text.pdf) | [Drive link](https://colab.research.google.com/drive/1wkRxJvA8GPuoSXwJmlNTBcaKzxzXYTo3?usp=sharing) |
| 2    	 | 4       	 | Th  	 | 2/1  	  | Vector similarity and nearest-neighbors classification           	 | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_4_supervised_learning_nns.pdf)       | [Drive link](https://colab.research.google.com/drive/1L35Z4ZY_zumDHPo0K9bycU16xK8xuvG3?usp=sharing) |
| 3    	 | 5       	 | Tu  	 | 2/6  	  | Nearest-neighbors clustering   	                                   | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_5_clustering.pdf)                    | [Drive link](https://colab.research.google.com/drive/1pDU7BKcxmusfNnqUjfeLB2zN_eKRhQ45?usp=sharing) |
| 3    	 | 6       	 | Th  	 | 2/8  	  | Dimension reduction    	                                           | 	                     | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_6_dimension_reduction.pdf)           | [Drive link](https://colab.research.google.com/drive/12u4Rm8O3_ejXpATsgFZRQqqZEJ3XXGHv?usp=sharing) |
| 4    	 | 7       	 | Tu  	 | 2/13 	  | Basics of statistical language modeling    	                       |                       | [PDF](https://shcarton.github.io/assets/course_material/cs759spring2024/lectures/lec_7_stat_lang_modeling.pdf)            | [Drive link](https://colab.research.google.com/drive/1EfsE4gKbhVqV4x7lCWFdlmrJ6KlN_HC7?usp=sharing) |
| 4    	 | 	 -       | Th  	 | 2/15 	  | Class cancelled                           	                        | HW 1 	              	 |                                                                                                                           |                                                                                                     |
| 5    	 | 8       	 | Tu  	 | 2/20 	  | More statistical LMs and Naive Bayes  	                            |                       |                                                                                                                           |                                                                                                     |
| 5    	 | 9      	  | Th  	 | 2/22 	  | Hidden Markov Models                  	                            | 	              	      |                                                                                                                           |                                                                                                     |
| 6    	 | 	10       | Tu  	 | 2/27 	  | Common NLP tasks and metrics                                       |                       |                                                                                                                           |                                                                                                     |
| 6    	 | 11      	 | Th  	 | 2/29  	 | Linear and logistic regression                   	                 | 	              	      |                                                                                                                           |                                                                                                     |
| 7    	 | 12      	 | Tu  	 | 3/5  	  | Introduction to PyTorch                             	              |                       |                                                                                                                           |                                                                                                     |
| 7    	 | 13      	 | Th  	 | 3/7  	  | Feedforward neural nets	                                           | 	              	      |                                                                                                                           |                                                                                                     |
| 8    	 | 14	       | Tu  	 | 3/12 	  | Word vector models                                                 |                       |                                                                                                                           |                                                                                                     |
| 8    	 | 15	       | Th  	 | 3/14 	  | Basic recurrent neural nets            	      	                    | 	                     |                                                                                                                           |                                                                                                     |
| -	     | -     	   | Tu  	 | 3/19 	  | Spring break-no class                            	                 | 	                     |                                                                                                                           |                                                                                                     |
| -    	 | -      	  | Th  	 | 3/22 	  | Spring break-no class                 	                            |                       |                                                                                                                           |                                                                                                     |
| 9    	 | 16      	 | Tu  	 | 3/26 	  | Sequence tagging with RNNs                              	          | 	               	     |                                                                                                                           |                                                                                                     |
| 9    	 | 17      	 | Th  	 | 3/28 	  | Language modeling with RNNs                      	                 |                       |                                                                                                                           |                                                                                                     |
| 10   	 | 18      	 | Tu  	 | 4/2  	  | Sequence-to-sequence models         	                              | 	               	     |                                                                                                                           |                                                                                                     |
| 10   	 | 19      	 | Th  	 | 4/4  	  | Transformers              	                                        |                       | [                                                                                                                         |                                                                                                     |
| 11   	 | 20      	 | Tu  	 | 4/9 	   | BERT and friends                               	                   | 	              	      |                                                                                                                           |                                                                                                     |
| 11   	 | 21      	 | Th  	 | 4/11 	  | Zero- and few-shot learning                           	            |                       |                                                                                                                           |                                                                                                     |
| 12   	 | 22      	 | Tu  	 | 4/16 	  | Prompt engineering                	                                | 	              	      |                                                                                                                           |                                                                                                     |
| 12   	 | 23      	 | Th  	 | 4/18 	  | Bias and fairness                         	                        | 	                     |                                                                                                                           |                                                                                                     |
| 13   	 | 24      	 | Tu  	 | 4/23 	  | Interpretability                           	                       | 	                     |                                                                                                                           |                                                                                                     |
| 13   	 | 25      	 | Th  	 | 4/25 	  | Text and images                            	                       |                       |                                                                                                                           |                                                                                                     |
| 14   	 | 26      	 | Tu  	 | 4/30  	 | Future of NLP                          	                           | 	                     |                                                                                                                           |                                                                                                     |
| 14     | 27        | Th    | 5/2     | Final exam                                                         | 	                     |                                                                                                                           |                                                                                                     |
| 15     |           | Tu    | 5/7     | Reading day                                                        |                       |                                                                                                                           |                                                                                                     |
| 15     |           | Th    | 5/11    | Exams week                                                         |                       |                                                                                                                           |                                                                                                     |
| 16     |           | Tu    | 5/16    | Exams week                                                         |                       |                                                                                                                           |                                                                                                     |
{:.tg}

