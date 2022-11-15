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
- Are commenters interested only in one area or they are engaged in both artistic and scientific videos?
- If commenters are interested in both, are they commenting at around the same time or in different phases (months, years)?
- What percentage of the youtube videos corresponds to scientific and artistic videos ?

## 3 Tools
External libraries:

### 3.1 Proposed additional datasets (if any)
At the moment, the work is based solely on YouNiverse dataset

### 3.2 Methods
To classify “artistic” videos we are using seven arts subdivision (cinema, paintings, architecture, sculptures, literature, theatre, and music) and mapping keywords for each area to artistic category. We are excluding music area as some people listen to it on YouTube without any visualizations and in general high number of population listens to music no matter their interests. 
1.	Define what is considered as artistic videos
2.	Select artistic videos by keywords matching
3.	Group comment file by author, select authors that have at least a certain number X (defined later) of comments
4.	Make the link between commented video and to which category (artistic/scientific) it belongs
5.	Check distribution of commenters on one and both categories types
6.	For commenter on two categories, check if they mix both types of videos in the same time period or in different time phases.

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