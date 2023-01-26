# Accenture-Virtual-Intership
Virtual Experience Program

# CASE STUDY
Social Buzz was founded by two former engineers from a large social media conglomerate, one
from London and the other from San Francisco.

Due to their rapid growth and digital nature of their core product, the amount of data that they
create, collect and must analyze is huge. Every day over 100,000 pieces of content, ranging
from text, images, videos and GIFs are posted.

You’ve been assigned to a new project and the first thing you must do is get up to speed with the 
business problem that this project is tackling, the requirements that need to be fulfilled as 
deliverables and the alignment of internal teams with the client. 
You will be working within a large team at Accenture and there will be several people on your
team doing different roles to make this project a success. 

As a data analyst, it is imperative that you have a solid understanding of the project as quickly as possible. 
A data analyst sits between the business and the data, so it’s important that you have a deep understanding from both sides to provide insights. 

You need to use the client brief to:

* Understand the client and business problem at hand.

* Identify the requirements that need to be delivered for this project.

* Identify which tasks you should focus on.

* To make sure that you have understood the project, you will be tested on an outline of the business problem, the requirements and the delegation of tasks.

The goal is to categorize top perfomring contents on the platform by users while maintatining appropriate data practices for data collection and use.

# BUSINESS TASK:
An audit of their big data practice
- Recommendations for a successful IPO
- An analysis of their content categories that highlights the top 5 categories with the
largest aggregate popularity

# Tasks to do





# Use Case

# DataSet Summary and Data Model:
* User *

 ID: Unique ID of the user (automatically generated) Name: Full name of user

 Email: 
 
 Email address of user Profile

 User ID: 
 
 Unique ID of a user that exists in the User table Interests: Interests of the associated user

Age:

Age of the associated user Location

User ID: 
Unique ID of a user that exists in the User table Address: Full address of the user
Session

User ID: 

Unique ID of a user that exists in the User table

Device: 

Mobile device that they used for this session on the application

Duration:

Amount of time in minutes that this user stayed active on the application during this session
Content

ID:

Unique ID of the content that was uploaded (automatically generated) User ID: Unique ID of a user that exists in the User table

Type: 

A string detailing the type of content that was uploaded

Category:

A string detailing the category that this content is relevant to URL: Link to the location where this content is stored
Reaction

Content ID: 

Unique ID of a piece of content that was uploaded

User ID: 

Unique ID of a user that exists in the User table who reacted to this piece of content Type: A string detailing the type of reaction this user gave

Datetime:

The date and time of this reaction

 # ReactionTypes
Type: A string detailing the type of reaction this user gave

Sentiment: A string detailing whether this type of reaction is considered as positive, negative or neutral

Score: This is a number calculated by Social Buzz that quantifies how “popular” each reaction is. A reaction type with a higher score should be considered as a more popular reaction.
