---
layout: page
title: Project 2
permalink: /projects/project-2
parent: Projects
nav_order: 2
---

# Overview

Welcome to the second phase of the course project! In the first phase, we delved into the Music player repository, and understood its code structure. In this second phase, we will continue our exploration of Music by expanding its capabilities and functionality using software engineering principles. This phase will focus on enhancing Music's features to make it more useful and user-friendly. 

## GitHub Classroom

You will be continuing to work on the same repository that you used in the first phase of the project.

# Specification 

You need to extend Music to support each feature described below using appropriate design patterns. You may need to refactor existing code to support this. Use at least 2-3 different design patterns, excluding trivial patterns such as singleton pattern. You will be graded on efficient and precise use of design patterns.  
Note that the changes to the frontend do not need to be extensive and you will not be graded on this.    

## Feature 1: Better user management

Our music player has a user management system already in place, which you have already looked at in detail. The current flow of creating a user involves logging into an admin account and creating a new user manually. These new users can add new music to the library. However, this is neither intuitive nor convenient, and thus demands an improvement. Allow for the creation of new users directly from the login page.

## Feature 2: Better library management

In the current codebase, songs added by a user to Music are visible to everyone. This is not ideal - not everyone wants to share all their music. Modify Music so that songs added by a user can be hidden from other users. Additionally, playlists created by a user are visible only to them. We want to modify Music to allows users to choose whether their created playlists should be visible to other users or not. A public playlist can be interacted with by other users (e.g. songs can be added to it).

## Feature 3: Online Integration

Music already support some degree of online integration. However, it is limited to only one service - LastFM. We want to extend what you can do with LastFM, and also incorporate integration with Spotify.  

In particular, Music should support the following features -

1. Search for songs: LastFM and Spotify both allow you to search for songs. Use their APIs to allow users to search for songs in Music. Note that it should be possible for the user to choose which service to use.  
2. Recommend songs based on playlist: Music allows users to create playlists. Spotify and Lastfm allow users to get recommendations similar to provided songs. Putting two and two together, we want to allow Music users to get recommendations from these services based on existing playlists. Concretely, given a list of songs, we want recommended songs from Spotify or LastFm (based on users choice). A simple string representation of these recommendations is enough. 

## Bonus Feature: Even better library management 
You have already improved how playlists work in Music. Let's extend this further. Users should be now able to designate public playlists as collaborative playlists. Only these playlists can be interacted with by all users, while a default public playlist should be read-only (i.e users can view songs in it but not add songs to it).   

# Submission Guidelines

- All the above code needs to be pushed in `main` branch of the same github repository alloted to you.
- You need to submit a report containing the details of implementation, including the design patterns used and any changes made to existing code. The report should be present in the docs directory, titled `project2_<team_number>.pdf`. Accurately report the contribution of each team member at the end of this report.  
- In case you attempt the bonus feature, you need to submit a separate report titled `project2_bonus_<team_number>.pdf`.

Soft deadline: 24rd March, 2023  
Hard deadline: 31th March, 2023  

The course policy menitioned on this website will be followed for late submissions and associated penalties/late days.
