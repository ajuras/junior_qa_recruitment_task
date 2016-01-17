An example of an interview assignment for Junior QA Specialist.

# ASSIGNMENT

Imagine that you are in charge of testing an online social networking and microblogging application. It enables registered users to read and send short text messages. Please assume that it’s available only as a web page. You can use Twitter as reference. Using Google Docs prepare a step by step checklist of testing such an application. Try to include tasks that will take no longer than 30 minutes in total to execute. Explain why you find each of them important.
 
# ANSWER

## Introduction

The form of the task and the limited timeframe (30 minutes for all test tasks in total) forced me to be very brief and to make a number of simplifications in certain areas of the test areas suggested below. Nevertheless, I still believe that I succeeded to show the mastery of at least basics of testing theory and practice.

I have assumed that I am to test a simple web application that implements the following four user stories:

 * USER STORY 1: As an anonymous user, I can create a user account (I can sign up).
 * USER STORY 2: As a previously registered user, I can log in.
 * USER STORY 3: As a logged in user, I can read all published posts.
 * USER STORY 4: As a logged in user, I can create a new post up to 160 characters in length.

I have prioritised these four user stories as the most important, because I take them to constitute a minimum viable product, as defined in Scrum.

As the next most important feature I would suggest to implement the possibility of updating (editing) already published posts, e.g. in order to comply with the Polish law requiring the administrator to edit out illegal content (such as hate speech).

I am also acutely aware of a huge number of other features that will be requested: updating and deleting user accounts, updating (editing) users’ own posts (and following from that: the need to define user roles (user, moderator, admin) and their permissions), the ability to comment on other users’ posts and/or share the posts. In order to keep my answer brief and to the point, I decided to focus thoroughly on the first four user stories first.

Also, while deciding on the prioritisation, I was asking myself the following questions:

 * What things will users do most often with this application?
 * What areas of this application are most likely to contain show-stopping defects?
 * What parts of this application are critical to the business?
 * Are any parts of this application governed by legal or regulatory agencies?

What follows is my plan for black-box functional (both positive and negative) tests for such an application. You can see the test cases in the test_cases.md file.