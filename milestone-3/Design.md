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

* Git Repo: Mark-Seaman.github.io




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

  **class UserSerializer(serializers.ModelSerializer):
    """
    Serializer for the User table.
    """
    class Meta:
        model = User
        fields = ('userid',
                  'twitterhandle',
                  'email',
                  'password')
  
  **class PostSerializer(serializers.ModelSerializer):
    """
    #Serializer for the Post table.
    """
    class Meta:
        model = Posts
        fields = ('postid',
                  'tweet',
                  'userid',
    
    
   **class PostReactionsSerializers(serializers.ModelSerializer):
    """
    #Serializer for the PostReactions table.
    """
    class Meta:
        model = PostReactions
        fields = ('reactionsid',
                  'postlikes',
                  'postcomments')
                  
                  
                  
    **class CommentRepliesSerializers(serializers.ModelSerializer):
    """
    #Serializer for the CommentReplies table.
    """
    class Meta:
        model = CommentReplies
        fields = ('commentsid',
                  'postcomments')             
    
    


### Implement views


### Implement URL routes
