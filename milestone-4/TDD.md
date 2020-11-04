# Milestone 4.  - Test-Driven Development
## PROJECT INFO
- [Software project plan](https://github.com/Twitter-Clone/twitter-clone-documentation)
- Other Roles - [Requirements.md](https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-4/Requirements.md) , [Design.md](https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-4/Design.md) , [Test.md](https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-4/Test.md) , [Code.md](https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-4/Code.md)
- File: Milestone-4/Code.md
- URL: https://github.com/Twitter-Clone/twitter-clone-documentation/blob/master/milestone-4/Code.md
- Documents: twitter-clone-documentation/tree/master/docs
- Git Repo: https://github.com/Twitter-Clone
## Milestone 4. Functionality Complete

Role - Programmer - Test-Driven Development

### Use Test-driven workflow

* Updated test file for api [tests.py](https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/tests.py)
* Using existing: 
    * views [views.py](https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/views.py) 
    * models [models.py](https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/models.py)
    * serializer [serializer.py](https://github.com/Twitter-Clone/twitter-clone-api/blob/master/tcapi/serializer.py)

- Added tests for the following api 'table' models: User, Posts

* Users are tested under the UserTableTests class:

    * creation of one user object (test_add_user)
    
    * creation of two user objects (test_add_users)
    
    * retrieving all users (test_get_all)
    
    * retrieving one user (test_get_user)
    
    * retrieving two users (test_get_users)
    
    * deleting one user (test_delete_user)
    
    * deleting all users (test_delete_users)
    
    * changing one user's email (test_update_user)
    
    * changing two users' passwords (test_update_users)
    
    * changing all users' passwords (test_update_all)
    
* Posts are tested under the TweetTableTests class:

    * creation of one post object (test_add_tweet)
    
    * creation of two post objects (test_add_tweets)
    
    * retrieving all posts (test_get_alltweets)
    
    * retrieving one post (test_get_tweet)
    
    * retrieving two posts (test_get_tweets)
    
    * deleting one post (test_delete_tweet)

    * deleting two posts (test_delete_tweets)
    
    * deleting all posts (test_delete_all)
    
    * changing one post's tweet (test_update_tweet)
    
    * changing two posts' tweets (test_update_tweets)
    
    * changing all posts' tweets (test_update_all)

- Edited tests and utilized them to fix issues with communication between the frontend and the database

### Implementation Cycle

- Using the ERP implementation cycle, orientation and strategy formulization

1. Orientation

1. Strategy Formulization

1. **Design and launch a knowledge management initiative**

1. Expand and support

1. Institutionalize knowledge management

### Implement all core features

- Users are able to create new accounts

- Users are able to create new posts

- Posts are able to get sent to the database from the front-end with the api

- Posts are retrieved from the database to the front-end with the api


##Milestone #4 Team Survey


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
    
Christian - (3/3 credits)
    _x_ participated in team meetings
    _x_ was cooperative
    _x_ delivered contribution
```
