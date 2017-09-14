# README

# User stories
***

# Database (DB)
## ERD (Entity Relationship Diagram)
![erd database](/docs/images/erd.png)

# DB Tables
I made 3 tables for my app, User, Tweet and Profile. User stores the user information like password etc. Tweet stores the information message that a user tweets and the Profile table stores information about the user. Each user has one Profile and many Tweets.

## User
- email
- password

## Profile
- avatar
- first_name
- last_name
- country
- user id (belongs_to)

## Tweet
- message
- user id (belongs_to)


# Pages
## homepage
- tweets on page
- log in/ log out

## tweet show page
- see tweet
- edit tweet (if logged in)

## profile page
- first name, last name
- tweet count
- avatar
- country
- edit ability

# Figma (wireframe)
***