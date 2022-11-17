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
We are often put into boxes regarding our interests and hobbies, we have friends that have the same interests as us, we chose a department when we are young at high school and social media makes a lot of suggestions based on our past interests. We sometimes hear that artistic and scientific people are different, closed-minded in their subject and not interested in the other one. The main goal of this project is to study this stereotype by using the YouNiverse dataset using comments and video metadata files. We want to determine whether comment authors that have at least a particular amount of comments solely comment on one or both of the following categories: artistic/scientific, or both. We can examine whether it's true or not that the majority of profiles that comment on art videos never comment on scientific videos. To draw some conclusions about people’s interests, we can determine if the profiles that consider both types of videos mix them together over one time period or if they are more evenly distributed over several.

## 2. Research Questions
- How do we define art in YouTube videos, since there is no "Art" category?
- How do we distinguidh different types of arts in YouTube videos ?
- How do we distinguidh different types of sciences in YouTube videos ?
- What percentage of the youtube videos corresponds to scientific and artistic videos ?
- What type of art (visual, literary, performing) and sciences (technical, theoretical) are the most popular ?
- How does this popularity evolve in time ?
- How many comments make a comenter in average on youtube ?
- Do people comment more scientific or artistic videos ?
- Are commenters interested only in one area or they are engaged in both artistic and scientific videos?
- If commenters are interested in both, are they commenting at around the same time or in different phases (months, years)?

## 3 Tools
External libraries:

### 3.1 Proposed additional datasets (if any)

### 3.2 Methods

#### Contraints  
1.  Keep only 100 000 comenters and the videos they commented 
2.	Our artistic videos are split in three groups: visual art, literary art, performing art
3.  Our scientific videos are split in two groups: technical sciences, theoretical sciences

#### Milestone 2
1.  Prepare a dataset with 100 000 comenters and the videos they commented
2.  Select only relevant features
3.  Define a dictionary to select visual art, literary art and performing art videos
4.  Define a dictionary to select technical sciences and theoretical sciences videos
5.  Use keyword matching between these dictionaries and the videos to classify them
6.  EDA of the artistic and scientific videos 
7.  EDA of the comenters dataset

#### Next tasks
1.  Select all the comenters that commented on scientific or artistic videos
2.  Categorise users as scientific, artistic, none of them or both of them
3.  Compute the percentage of comenters who commented on scientific videos within the 100 000 different comenters (same for artitic and sub-categories videos)
4.  Compute the percentage of artistic comenters who commented on scientific videos (vice-versa and sub-categories)
5.  Analyze the percentage differences in the groups to know if there is a statistical significance
6.  Plot the distribution of the numbers of scientific commented by the 100 000 commenters (same for artitic and sub-categories videos)
7.  Plot the distribution of the numbers of scientific commented by the artistic commenters (vice-versa and sub-categories)
8.  Compare the different distributions by superposing them and use a wilcoxon test
7.  Analyze the percentage of scientific comenters which comment on artistic videos over time (vice-versa and sub-categories)
8.  Use all our previous analysisis to draw a conclusion about our research question

## 4 Organization
### 4.1 Proposed timeline
In the following weeks we are planning to analyze more users commenting on both video types and deepen our current work:
* 21 November – 27 November 
* 28 November – 4 December Implement milestone 2 feedback, 
* 5 December – 11 December Prepare visualizations
* 12 December – 23 December work on user story and finalize the project
### 4.2 Team organization

Kelyan: 


Gaston: 

Sushen:

Ekaterina:

## Questions for TAs (optional)