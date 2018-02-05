# StudyGroup
### Functional Specification

A. Scott Tribble
Last Updated: Sunday, 4 February 2018.

## Overview

StudyGroup is a web-based service that lets people in a given group know where/when someone will be out studying.  
    
It also allows for people to add visited locations to a database with comments (and perhaps ratings).

This spec is not, by any stretch of the imagination, complete.  This is not the final version  and is likely to change.

This spec does not discuss technical information, it just discusses what the user will see as they interact with the StudyGroup app.

## Scenarios

#### Scenario 1:  Scott.
Scott is a student enrolled in a full-time web-development bootcamp that is an online school.  One afternoon, she decides that it would be REALLY NICE to leave her house and finish-up her schoolwork around some other people studying similar things.  Luckily, there are other students enrolled in the same school (although not her particular course) who use StudyGroup.  Scott logs-in and sees that Sally is studying right down the road, right now. She high-tails it to the cafe.

#### Scenario 2:  Mo.
Mo works full-time as a social worker but would really like to attend a web-development bootcamp.  She is working through some pre-requisites for an in-person course, but she is having a little trouble with a few concepts and could really use some help.  Since she isn't in school, yet, she doesn't have classmates to ask.  Luckily, she has some friends who are programmers or in school for computer stuff, and they all like to get together for coding.  She made them all a StudyGroup, and now she can post that she will be studying on Sunday from 8am-3pm at Anna Bananna's, with the comment that she could use some help.  One of her friends checks his StudyGroup, sees that she'd like some help, and stops in.


## Non Goals

This version will not support the following features:

  - Multiple time-zones for one member.  I will assume all members of  a single group are in the same geographical location.
  - Changing passwords.

This version may not support the following features:

  - Mutiple groups per user.
  - Google API requests for location information.
  - Rating system for locations.

