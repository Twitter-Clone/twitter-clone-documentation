# Milestone 3. Core Features Implemented - Design


## PROJECT INFO

* [Software Project Plan - Twitter-Clone](../Index.md)

* Other Roles - [Requirements.md](Requirements.md)
, [Design.md](Design.md)
, [Code.md](Code.md)
, [Test.md](Test.md)



* File: Milestone-3/Design.md

* URL:https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-3/Design.md

* Documents: Documents/swplan/BookBuilder





### Milestone 3. Core Features Implemented



Role: Designer - Design

Goal: Component Design - API

* Prototype - development spike of core functionality
* Implement data models
* Implement views
* Implement URL routes



## Twitter-Clone - Component Design - API



### Prototype - development spike of core functionality
  * One core set of features that the team decided to do for this project are:
    * Users can create an account.
    * Users can 'tweet' their thoughts.
    * Users can edit their account such as changing the username/password.
    * Users can comment and like on others posts. 


### Implement data models
* Data models are included for users, posts, post reactions, and comment replies

 ### Users
  * userid
  * twitterhandle
  * email
  * password
 
 ### Posts
  * postid
  * tweet
  * userid
 
 ### PostReactions
  * reactionsid
  * postlikes
  * postcomments
  
 ### Comment Replies
  * commentsid
  * postcomments
  
  
  Data model can be found at: https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/models.py
    


### Implement views
* So far, views have been implemented for the users. We currently have user_list and user_detail.
* Both user views have attributes for GET, POST, and DELETE. 
* User views can be found at: https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/views.py
* Views for the comment replies table, post reactions table, and the posts table still need to be implemented. 
* The views that still need to be implemented are documented under issues so that the team knows the next steps to take. 
* As of right now, the team has one tests.py file which is mainly responsible for testing the connection to the API. 


### Implement URL routes
* URL routes have been initialized for the user_list and user_detail
* More URL routes will be initialized for the comment replies table, post reactions table, and posts table by the next milestone. 

### Document Engineering Practices
* As a team, we all work best when we are talking to eachother and sharing out screens. This allows for those of us who are not doing to acutal
code to take notes and observe what is happening. 
* Rules for TDD: 
* 1. Work together
* 2. Do small bits of code at a time. No more than two lines of code.
* 3. If the code is broken, do not move on until it is fixed. This can cause to more bugs within a few short moments. 
* 4. Fix it then break it and repeat to fully understand what the code is doing. 
* 5. Document the issues that cannot be resolved. 


##Milestone #3 Team Survey
```
Matt - (3/3 credits)
    _x_ participated in team meetings
    _x_ was cooperative
    _x_ delivered contribution
    
Ashley - (3/3 credits)
    _x_ participated in team meetings
    _x_ was cooperative
    _x_ delivered contribution
    
Doug - (3/3 credits)
    _x_ participated in team meetings
    _x_ was cooperative
    _x_ delivered contribution

Sean - (3/3 credits)
    _x_ participated in team meetings
    _x_ was cooperative
    _x_ delivered contribution
``` 
