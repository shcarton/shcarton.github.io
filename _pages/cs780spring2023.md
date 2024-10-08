---
layout: page
title: CS780/880 Spring 2023
permalink: /cs780spring2023/
description: "CS780/880 - Natural Language Processing"
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
| 1/24/2022  | 5/4/2022 | Tue/Thurs | 3:40pm - 5:00pm | PARS NB22 |
{:.tg}


<br/>

**Office hours:** Thursdays 5:10pm - 6:00pm, location: Kingsbury Hall W224

**Prerequisites:** CS 515 (or equivalent) and MATH 539 or MATH 644

**Description:** This class covers natural language processing, including both methods and well-known applications. Methods discussed will range from classical probabilistic methods such as Naive Bayes and Hidden Markov Models, to contemporary neural network methods, including word vector models, recurrent neural networks, and Transformer-based models. Applications discussed will include text classification, machine translation, and conversation systems (among others).

## Syllabus


Updated: 2/6/2023

### Important announcements
There are a couple of key things that students in this course need to know.

**Syllabus subject to change**
This syllabus is subject to change. I will make an announcement when this happens, but it is on you as students to keep up. 

**Mandatory reporter**
I am a mandatory reporter. What this means is if I hear about a situation where a student is being or has been sexually harassed, assaulted, stalked, or otherwise endangered, I am legally obligated to file a report with the UNH DEI office. That said, I am more than happy to help students find guidance in dealing with these types of situations, subject to my reporting requirements.

### Course overview

This course is a special topics lecture on natural language processing for graduate students and advanced undergraduates. Every class session will consist of a lecture, with a weekly homework assignment due the following week. Homeworks will be distributed and completed in Python as Google Colab notebook, with the exact details of distribution and submission to follow. 

There is no midterm nor final exam. 

There will be a final project, chosen from a list of potential topics, with a milestone check-in, a final submission, and a mandatory poster session at the end of the semester. 

There is no required textbook, nor mandatory readings. 

### Grading distribution

The grading distribution is as follows:
<br/>65% - Weekly homeworks
<br/>25% - Final project and poster presentation
<br/>10% - Attendance and classroom activities

### Late policy

Homeworks and project milestones can be turned in up to 5 days late, with a stacking 10% per-day penalty on the maximum possible grade, before receiving a zero. 

### Attendance policy
In-person attendance is encouraged and 10% of the final grade will be based on attendance and participation in discussion and classroom activities.

I am happy to accommodate life events. If you get COVID or have some other pressing reason to attend remotely, I can temporarily move the class to a hybrid format. I’m also happy to grant excused absences for medical or family problems, or various other kinds of emergencies. Let me know as early as possible if you need either of these kinds of accommodation. 

### Academic honesty policy

Students are welcome to ask for and give each other assistance on the homework assignments, but these assignments should be completed individually and your work should be your own. 

Given the specialized nature of the topic, it is unlikely that AI coding tools such as ChatGPT will be effective in completing the weekly homework assignments. But needless to say, the use of these kinds of tools is not allowed. 

Generally speaking, I will follow the [UNH academic honesty policy](https://catalog.unh.edu/graduate/academic-regulations-degree-requirements/academic-honesty/), which lays out what is considered cheating and what the process is for dealing with cases of reported academic dishonesty.

### Schedule

| Week 	 | Lecture 	 | Day 	 | Date 	 | Description                                	       | Assignment Due 	     | Slides                                                                                                                    | Notebook                                                                                               |
|--------|-----------|-------|--------|----------------------------------------------------|----------------------|---------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| 1    	 | 1       	 | Tu  	 | 1/24 	 | Introduction to NLP                        	       | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_1_intro_to_NLP.pdf)                  |                                                                                                        |
| 1    	 | 2       	 | Th  	 | 1/26 	 | Basics of linguistics                      	       | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_2_overview_of_linguistics.pdf)       |                                                                                                        |
| 2    	 | 3       	 | Tu  	 | 1/31 	 | Representing text numerically              	       | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_3_numerically_representing_text.pdf) | [Drive link](https://colab.research.google.com/drive/1O8GKZdemXfP8HgeJtO36VnEMGQV4mnyI?usp=sharing)    |
| 2    	 | 4       	 | Th  	 | 2/2  	 | Nearest-neighbors classification           	       | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_4_supervised_learning_nns.pdf)       | [Drive link](https://colab.research.google.com/drive/1Et76oSgqHNmZ4Efo_xGlU98BuIaPn-nF?usp=sharing)    |
| 3    	 | 5       	 | Tu  	 | 2/7  	 | Nearest-neighbors clustering   	                   | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_5_clustering.pdf)                    | [Drive link](https://colab.research.google.com/drive/10ebGWX-XfIuN3vNFtzmQvEpsyeWm0NuX?usp=sharing)    |
| 3    	 | 6       	 | Th  	 | 2/9  	 | Dimension reduction    	                           | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_6_dimension_reduction.pdf)           | [Drive link](https://colab.research.google.com/drive/1v5JLq-5-aqUmO0yInjoAhQ3CuIToPSzB?usp=sharing)    |
| 4    	 | 7       	 | Tu  	 | 2/14 	 | Basics of statistical language modeling    	       | HW 1 (Mon 2/13)      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_7_stat_lang_modeling.pdf)            | [Drive link](https://colab.research.google.com/drive/16ZkUP6JbkNsmrFqqrv9DODj4PDxak01L?usp=sharing)    |
| 4    	 | 8       	 | Th  	 | 2/16 	 | Naive Bayes                                	       | 	              	     | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_8_naive_bayes.pdf)                   | [Drive link](https://colab.research.google.com/drive/17lEk-r8-BjblCnEm5noW4L3x8UsgoPpN?usp=sharing)    |
| 5    	 | 9       	 | Tu  	 | 2/21 	 | Hidden Markov Models                       	       |                      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_9_hidden_markov_models.pdf)          |                                                                                                        |
| 5    	 | 10      	 | Th  	 | 2/23 	 | Common NLP tasks and metrics               	       | HW 2	              	 | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_10_tasks_and_metrics.pdf)            |                                                                                                        |
| 6    	 | 	         | Tu  	 | 2/28 	 | Class canceled                        	            |                      |                                                                                                                           |                                                                                                        |
| 6    	 | 11      	 | Th  	 | 3/2  	 | Linear and logistic regression                   	 | 	              	     | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_11_linear_logistic_regression.pdf)   | [Drive link](https://colab.research.google.com/drive/1tTxxhYZOOaYp3NWUS6mdcQrNwIuALLYr?usp=sharing)    |
| 7    	 | 12      	 | Tu  	 | 3/7  	 | Introduction to PyTorch                             	 |                      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_12_training_with_pytorch.pdf)        | [Drive link](https://colab.research.google.com/drive/1BQB9bkCYFhPyfPAJe2_V7iZ0K9Bp7FRb?usp=sharing)    |
| 7    	 | 13      	 | Th  	 | 3/9  	 | Feedforward neural nets	                           | HW 3	              	 | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_13_ffns_and_pytorch_lightning.pdf)   | [Drive link](https://colab.research.google.com/drive/1FYMvQaYStqVTMzBLlbCbtxivth7-OyQa?usp=sharing)    |
| -    	 | 	         | Tu  	 | 3/14 	 | Spring break-no class                              |                      |                                                                                                                           |                                                                                                        |
| -    	 | 	         | Th  	 | 3/16 	 | Spring break-no class             	      	         | 	                    |                                                                                                                           |                                                                                                        |
| 8    	 | 14      	 | Tu  	 | 3/21 	 | Word vector models                            	    | 	                    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_14_word_vectors.pdf)                 | [Drive link](https://colab.research.google.com/drive/1mvf3X4vreYm8VRhDHog-3GtIOmT1OZ4k?usp=share_link) |
| 8    	 | 15      	 | Th  	 | 3/24 	 | Basic recurrent neural nets                	       |                      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_15_rnns.pdf)                         | [Drive link](https://colab.research.google.com/drive/1mvf3X4vreYm8VRhDHog-3GtIOmT1OZ4k?usp=share_link) |
| 9    	 | 16      	 | Tu  	 | 3/28 	 | Sequence tagging with RNNs                              	 | 	HW 4               	 | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_16_rnn_sequence_tagging.pdf)         | [Drive link](https://colab.research.google.com/drive/1mvf3X4vreYm8VRhDHog-3GtIOmT1OZ4k?usp=share_link) |
| 9    	 | 17      	 | Th  	 | 3/30 	 | Language modeling with RNNs                      	 |                      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_17_rnn_lm_prompt.pdf)                |                                                                                                        |
| 10   	 | 18      	 | Tu  	 | 4/4  	 | Sequence-to-sequence models         	              | 	               	    | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_18_seq_to_seq.pdf)                   | [Drive link](https://colab.research.google.com/drive/1w3nns_OGK64pNlTizitDH38qM4UnJqWJ?usp=sharing)    |
| 10   	 | 19      	 | Th  	 | 4/6  	 | Transformers              	                        | FP paper selection   | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_19_transformer.pdf)                  | [Drive link](https://colab.research.google.com/drive/1PY11yEvClMokC9IFl0tk6gU3Kow1gFCY?usp=sharing)    |
| 11   	 | 20      	 | Tu  	 | 4/11 	 | BERT and friends                               	   | 	              	     | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_20_bert_etc.pdf)                     |                                                                                                        |
| 11   	 | 21      	 | Th  	 | 4/13 	 | Zero- and few-shot learning                           	 |                      | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_21_zero_few_shot.pdf)                | [Drive link](https://colab.research.google.com/drive/1qZ4cl1XXKdyn0gkQ7exWnB4Al5vL3s6e?usp=sharing)    |
| 12   	 | 22      	 | Tu  	 | 4/18 	 | Prompt engineering                	                | 	              	     | [PDF](https://shcarton.github.io/assets/course_material/cs780spring2023/lectures/lec_22_prompt_engineering.pdf)           |                                                                                                        |
| 12   	 | 23      	 | Th  	 | 4/20 	 | Bias and fairness                         	        | 	                    |                                                                                                                           |                                                                                                        |
| 13   	 | 24      	 | Tu  	 | 4/25 	 | Interpretability                           	       | 	                    |                                                                                                                           |                                                                                                        |
| 13   	 | 25      	 | Th  	 | 4/27 	 | Text and images                            	       |                      |                                                                                                                           |                                                                                                        |
| 14   	 | 26      	 | Tu  	 | 5/2  	 | TBD                          	                     | 	HW 5                     |                                                                                                                           |                                                                                                        |
| 14     | 27        | Th    | 5/4    | The future of NLP                                  | FP rough draft	      |                                                                                                                           |                                                                                                        |
| 15     |           | Tu    | 5/9    | Reading day                                        |                  |                                                                                                                           |                                                                                                        |
| 15     |           | Th    | 5/11   | Exams week                                         |                      |                                                                                                                           |                                                                                                        |
| 16     |           | Tu    | 5/16   | Exams week                                         | FP final draft       |                                                                                                                           |                                                                                                        |
{:.tg}

