# Busting the left brain vs. right brain myth?

## Table of contents:
- [Busting the left brain vs. right brain myth?](#busting-the-left-brain-vs-right-brain-myth)
  - [Table of contents:](#table-of-contents)
  - [1. Abstract](#1-abstract)
  - [2. Research Questions](#2-research-questions)
  - [3 Tools](#3-tools)
    - [3.1 Proposed additional datasets (if any)](#31-proposed-additional-datasets-if-any)
    - [3.2 Methods](#32-methods)
      - [Constraints](#constraints)
      - [Milestone 2](#milestone-2)
      - [Next tasks](#next-tasks)
  - [4 Organization](#4-organization)
    - [4.1 Proposed timeline](#41-proposed-timeline)
    - [4.2 Team organization](#42-team-organization)
  - [Questions for TAs (optional)](#questions-for-tas-optional)


## 1. Abstract
We are often put into boxes regarding our interests and hobbies, we have friends with the same interests as us, we chose a department when we are young at high school and social media makes a lot of suggestions based on our past interests. We sometimes hear that artistic and scientific people are different, closed-minded in their subject, and not interested in the other one. As an example, there exists a popular myth according to which "left-brained" people are more logical whereas "right-brained" people are more creative.

<img src="images/leftbrain-rightbrain.jpg" alt="drawing" width="400"/>

The goal of this project is to study this stereotype by studying the YouNiverse dataset at our disposition using comments and video metadata files. We want to determine whether users who usually comment on artistic videos also comment on scientific videos (and vice-versa). Our goal is also to split artistic and scientific videos into smaller domains to analyze if this effect is influenced by the particular domain of science/art in which the user is interested. To draw some conclusions about people’s interests, we can determine the user profiles and the watching/commenting behaviors w.r.t. videos that do not usually match their profiles.


## 2. Research Questions
- What type of art (visual, literary, performing) and sciences (technical, theoretical) are the most popular?
- How does this popularity evolve?
- Are commenters interested only in one area or are they engaged in both artistic and scientific videos?
- If commenters are interested in both, are they commenting at around the same time or in different phases (months, years)?
- Is there a difference of cross-interest between science and art when we study domains of these fields?
- What is the difference in terms of artistic sensibility between people interested in technical-related science vs people interested in natural sciences?

## 3 Tools
External libraries:
```
pandas, numpy, matplotlib, seaborn, scipy, wordcloud, matplotlib_venn
```

### 3.1 Proposed additional datasets (if any)

None.

### 3.2 Methods

#### Constraints  
1.  Keep only around 600 000 users and the videos on which they commented.
2.  Our artistic videos are split into three domains: visual art, literary art, and performing art.
3.  Our scientific videos are split into two domains: technical sciences, and natural sciences.

#### Milestone 2
1.  Prepare a dataset with 600 000 users and the videos on which they commented.
2.  Select only relevant features.
3.  EDA of the videos.
4.  EDA of the comments.
5.  Define a dictionary to select visual art, literary art, and performing art videos.
6.  Define a dictionary to select technical sciences and theoretical sciences videos.
7.  Use keyword matching between these dictionaries and the videos to classify them.
8.  EDA of the artistic and scientific videos.

EDA: Exploratory Data Analysis

#### Next tasks
1.  Categorize users into user profiles we will define based on their commenting behaviors.
2.  Analyse the commenting behavior of "scientist" users vs "artistic" users
  1.  Using Wilcoxon signed-rank test (non-parametric because we cannot assume normality), we will compare a sample distribution of random users commenting on a certain type of video (e.g. natural science) vs a sample distribution of a specific user profile (e.g. visual art amateur user)
  2.  We will do this for every domain we have as well as for every user profile.
  3.  We might expand this to other youtube categories/profiles.
3. Based on the resulting matrix we will get from the previous point, we will analyze the most interesting combinations of user-profiles and domains and try to understand why there might be differences.
4.  Use all our previous analysis results to draw conclusions about our research questions.
5.  After the analysis, we will reflect upon our assumptions (consciously or unconsciously made) as well as limitations that we might have come across. Additionally, we will discuss things we might have overlooked and finish with an open question based on what we learned. 

## 4 Organization
### 4.1 Proposed timeline

In the following weeks, we are planning to categorize users with respect to their comments and compute the analysis defined previously.

* 21 November – 27 November: Categorize users and compute Wilcoxon tests matrix
* 28 November – 4 December: Implement milestone 2 feedback, analyze combinations of users and domains 
* 5 December – 11 December: Draw conclusions and prepare visualizations
* 12 December – 23 December: Work on the data story and finalize the project

![gantt](images/gantt_chart.png)
  
### 4.2 Team organization

Kelyan: Comments EDA, Scientific EDA, Artistic EDA

Gaston: Data Sampling and Preprocessing, Videos EDA

Sushen: Video EDA, Scientific EDA, Artistic EDA

Ekaterina: Scientific EDA, Artistic EDA

## Questions for TAs (optional)