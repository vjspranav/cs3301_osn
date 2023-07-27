---
layout: page
title: Option A - Cinestream
parent: Project 3
grand_parent: Projects
nav_order: 1
---

# Project Description - CineStream Platform

CineStream is an OTT startup. The aim of the company is to provide a platform for its users to watch the latest as well as all-time classic movies in all languages from the comfort of their homes. Unlike the traditional OTT platforms, CineStream will also provide users to watch movies streaming on other OTT providers' websites (like Netflix, Amazon Prime, etc.) by paying a nominal rent (pay-per-movie basis). Moreover, users will also have the option to request movies on the platform.  Based on availability, the movies will be made available to the user(s) who have raised the request. The users will be able to provide ratings, likes/dislikes and reviews for the movies upon watching. Further, to ensure a quality experience for the user, the CineStream platform presents the users with personalized recommendations. 

The CineStream platform provides a flexible subscription model to the users, allowing them to pay a monthly or yearly charge to the platform. Discounts will be provided on the subscription fee to a set of active users based on their involvement (ratings, reviews, etc.). The platform collects the user's metrics such as likes, time spent on movies, number of movies watched, etc., to enhance the overall experience continuously. 


# Main Constraints

- The system should be able to handle different types of workloads (some users may be interested in live streaming games, some movies, some popular series and each can be from different OTT platforms)
- At any point one user should be streaming content from only one platform (eg: same user cannot login from multiple devices and use multiple platforms)
- The system should be able to handle the continuous inflow of data from different streaming platforms and provide seamless experience to the users
- Due to privacy issues, the system should not store any sensitive data related to the users.  
- Maximum of only 2 devices should be supported (a user cannot login from more than 2 devices at the same time)
- The system should provide easy means for admins/maintainence team to get access to the different analytics with respect to platform use like number of users, response time, server utilization, throughput, etc.
- The developed system should be environment friendly. It should use appropriate means to ensure that the energy consumed or carbon footprint of the system is as less as possible.

You can assume that each of the OTT providers has exposed some APIs to gather content.


# Deliverables

## Task 1: Requirements and Subsystems
- List down the set of functional and Non-functional requirements. Mention what forms the key requirements (Architecturally Significant requirements) and why (please explain in a few lines, not more).
- List down the main subsystems and brief description of each subsystem
- Create a simple informal high-level overview of the system (you can use a simple box and arrow diagram)


## Task 2: Architecture Framework
- Follow the IEEE 42010 standard to identify different stakeholders, concerns and corresponding viewpoints and views
- What are some of the major design decisions? (Make use of Architecture decision records to capture them). List at least 3-4 major decisions. Keep track of continuous decisions that have been made throughout the project

## Task 3: Architectural Tactics and Patterns

- What are some of the architectural tactics (at least 4-5) that you plan to use and why? (brief description). How do they help achieve the extra/non-functional requirements?
- What pattern(s) do you plan to use for the implementation and why? (explain very briefly)
- Architecture diagram(s) - You can make use of UML (Component, use case, sequence, deployment (if necessary) or C4Model (Context, Container and Component)





## Task 4: Architecture Analysis

- Perform a simple implementation of a part of the system with this architecture and compare it with one other pattern of your choice, provide some quantification of at least 2 of the NFRs that you have considered (eg: response time, throughput, utilization, etc.). What do you have to say about trade-offs?


## Bonus: Demo of simple prototype system

- Create a working demo of a minimal prototype of the system. You can create multiple folders with some video files and each folder can be considered an OTT provider. Cinestream can stream content from multiple "providers" based on user subscription.


