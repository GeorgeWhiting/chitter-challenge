## Makers Academy Weekend Challenge 4 - Chitter Challenge

Week 4 - Databases

Challenge - Solo over one weekend - Write a little Twitter clone that will allow the users to post messages to a public stream.

Features:
-------

```

As a Maker
So that I can let people know what I am doing  
I want to post a message (peep) to chitter

As a maker
So that I can see what others are saying  
I want to see all peeps in reverse chronological order

As a Maker
So that I can better appreciate the context of a peep
I want to see the time at which it was made

As a Maker
So that I can post messages on Chitter as me
I want to sign up for Chitter

As a Maker
So that only I can post messages on Chitter as me
I want to log in to Chitter

As a Maker
So that I can avoid others posting messages on Chitter as me
I want to log out of Chitter

```

### To run:


- Clone this repository
- cd chitter-challenge
- bundle
- psql
- create database "chitter_development";
- \q
- run rake database:migrate
- rackup
- or visit https://enigmatic-forest-49781.herokuapp.com/

### To add:

- Make it look nice
- Password recovery
- replying to a thread
- tagging other registered users in a thread
- email notifications

### Screenshots

![](https://i.imgur.com/ETgh6tA.png)

![](https://i.imgur.com/QiHFEWR.png)
