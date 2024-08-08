# MySQL-Project-3 Social Media Analysis
Source: Shivan Kumar Case study Project work

# Problem:
To analyze the marketing strategies, understand customer sentiments, and identify key influencers.

#Database Schema

# Table 1: Users: 
Stores information about social media users, including user_id, username, email,
and date_joined.

# Table 2: Posts: 
Contains details about user-generated posts, including post_id, user_id (foreign
key from Users table), content, and post_date.

# Table 3: Comments: 
Stores comments made by users on posts, with comment_id, post_id
(foreign key from Posts table), user_id (foreign key from Users table), comment_text,
and comment_date.

# Table 4: Likes: 
Tracks user likes on posts, with like_id, post_id (foreign key from Posts table),
user_id (foreign key from Users table), and like_date.

# Table 5: Followers: 
Manages user following relationships, with follower_id, follower_user_id
(foreign key from Users table), following_user_id (foreign key from Users table), and
follow_date.


# TO FIND:

1)  Retrieve posts with the highest number of comments for each user.

2)  List users who have made comments on posts made by users they are following.

3) Find users who have not received any likes on their posts.

4) Find users who have not liked any post.

5) List users who have liked posts made by users they are following.
