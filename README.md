# Title :

## Table of contents:
- [Title :](#title-)
  - [Table of contents:](#table-of-contents)
  - [1. Abstract](#1-abstract)
  - [2. Research Questions](#2-research-questions)
  - [3 Tools](#3-tools)
    - [3.1 Proposed additional datasets (if any)](#31-proposed-additional-datasets-if-any)
    - [3.2 Methods](#32-methods)
  - [4 Organization](#4-organization)
    - [4.1 Proposed Timeline](#41-proposed-timeline)
    - [4.2 Team organization](#42-team-organization)
  - [Questions for TAs (optional)](#questions-for-tas-optional)


## 1. Abstract
We are often put into boxes regarding our interests and hobbies, we have friends that have the same interests as us, we chose a department when we are young at high school and social media makes a lot of suggestions based on our past interests. We sometimes hear that artistic and scientific people are different, closed-minded in their subject and not interested in the other one. The goal of this project is to study this stereotype by studying the YouNiverse dataset using comments and video metadata files. We want to determine whether comment authors that usually comment on artistic videos also comment on scientific videos (and vice-versa). Our goal is also to split artistic and scientific people into sub-art or sub-science categories to analyze if this effect is influenced by the type of science/art in which the comenter is interested. To draw some conclusions about people’s interests, we can determine if the profiles that consider both types of videos mix them together over one time period or if they are more evenly distributed over several.

## 2. Research Questions
- What type of art (visual, literary, performing) and sciences (technical, theoretical) are the most popular ?
- How does this popularity evolve in time ?
- Are commenters interested only in one area or they are engaged in both artistic and scientific videos ?
- If commenters are interested in both, are they commenting at around the same time or in different phases (months, years) ?
- Is there a difference of cross interest between science and art when we study sub-categories of these fields ? 

## 3 Tools
External libraries: Pandas, Numpy, Matplotlib, Seaborn, Scipy, Wordcloud

### 3.1 Proposed additional datasets (if any)

### 3.2 Methods

#### Contraints  
1.  Keep only 600 000 users and the videos they commented
2.	Our artistic videos are split in three groups: visual art, literary art, performing art
3.  Our scientific videos are split in two groups: technical sciences, natural sciences

#### Milestone 2
1.  Prepare a dataset with 600 000 users and the videos they commented
2.  Select only relevant features
3.  EDA of the videos
4.  EDA of the comments
5.  Define a dictionary to select visual art, literary art and performing art videos
6.  Define a dictionary to select technical sciences and theoretical sciences videos
7.  Use keyword matching between these dictionaries and the videos to classify them
8.  EDA of the artistic and scientific videos 

#### Next tasks
1.  Select all the comenters that commented on scientific or artistic videos
2.  Categorise users as scientific, artistic, none of them or both of them
3.  Compute the percentage of comenters who commented on scientific videos within the 100 000 different comenters (same for artitic and sub-categories videos)
4.  Compute the percentage of artistic comenters who commented on scientific videos (vice-versa and sub-categories)
5.  Analyze the percentage differences in the groups to know if there is a statistical significance
6.  Plot the distribution of the numbers of scientific commented by the 100 000 commenters (same for artitic and sub-categories videos)
7.  Plot the distribution of the numbers of scientific commented by the artistic commenters (vice-versa and sub-categories)
8.  Compare the different distributions by superposing them and use a wilcoxon test
9.  Determine confidence intervals using bootstraping
10. Analyze the percentage of scientific comenters which comment on artistic videos over time (vice-versa and sub-categories)
11. Use all our previous analysisis to draw a conclusion about our research question

## 4 Organization
### 4.1 Proposed timeline
In the following weeks we are planning to categorise users with respects to their comments and compute the analysis defined previously.
* 21 November – 27 November: Categorise users and compute statistics percentages
* 28 November – 4 December: Implement milestone 2 feedback, compare the distributions 
* 5 December – 11 December: Draw conclusions and prepare visualizations
* 12 December – 23 December: Work on user story and finalize the project
### 4.2 Team organization

Kelyan: Comment EDA, Scientific EDA, Artistic EDA

Gaston: Data Importation, Video EDA

Sushen: Video EDA, Scientific EDA, Artistic EDA

Ekaterina: Scientific EDA, Artistic EDA

## Questions for TAs (optional)