# Name

Alexia Newgord

# How many points have you earned?

0/100

# How many hours have you spent on this?

fill-in-your-answer

# When did you first start working on this week's learning challenges?

Saturday

# What is the most difficult part about this week's challenge?

fill-in-your-answer

# Show and tell (8 points)

## Link (2 points)

[Microsoft launches a machine learning service from its Azure cloud](http://venturebeat.com/2014/06/16/microsoft-launches-a-machine-learning-service-from-its-azure-cloud/)

## Discuss how you may apply the machine learning technique mentioned in this article to another interesting problem (6 points).

We can already see applications of this kind of technology in Google's new Machine Learning strategies for its online spreadsheets (see this [website](http://venturebeat.com/2014/10/13/google-uses-machine-learning-to-fill-in-the-blanks-in-your-spreadsheet/)).  

I think that highly accessible machine learning tools will be a great asset for small to mid-size companies that can't necessarily afford to research and design their own expensive machine learning technologies.  The article makes it sound that, when this project is formally released, it will be particularly useful for retail and other business intelligence.

# D3 IV

## Checkpoints (3 points x 4 = 12 points)

# 1. (3 points)

![image](cp1.png?raw=true)

[checkpoint](cp1.html)

# 2. (3 points)

![image](cp2.png?raw=true)

[checkpoint](cp2.html)

# 3. (3 points)

![image](cp3.png?raw=true)

[checkpoint](ccp3.html)

# 4. (3 points)

![image](cp4.png?raw=true)

[checkpoint](cp4.html)

## Challenges (4 points x 3 = 12 points)

# 1. (4 points)

![image](c1.png?raw=true)

# 2. (4 points)

![image](c2.png?raw=true)

# 3. (4 points)

![image](c3.png?raw=true)

[challenge3](c3.html)



# MongoDB II

## Checkpoints (6 points x 2 = 12 points)

### 1 (6 points)

[mongodb js code collecting github events about our course](2cp1.js)

### 2 (6 points)

![terminal output of mongodb query](2cp2.png?raw=true)

## Challenge 1 (4 points x 10 = 40 points)

### 1 (4 points)

> db.gitEvents.({"actor.login":"doubleshow"})

![screenshot](2c1.png?raw=true)

### 2 (4 points)

> db.gitEvents.findOne({"actor.login":"doubleshow"},{'actor':1})

![screenshot](2c2.png?raw=true)

### 3 (4 points)

> db.gitEvents.find({"actor.login":{$in:["actor.login","doubleshow"]}}, {'actor.login':1, 'created_at':1});

![screenshot](2c3.png?raw=true)

### 4 (4 points)

> db.gitEvents.findOne({'type':'PushEvent'});

![screenshot](2c4.png?raw=true)

### 5 (4 points)

> db.gitEvents.find({'type':{$in:["PushEvent"]}},{'payload.commits.author.name':1});
![screenshot](2c5.png?raw=true)

### 6 (4 points)

> db.gitEvents.findOne({'type':{$in:["IssueCommentEvent"]}},{'payload':1});

![screenshot](2c6.png?raw=true)

### 7 (4 points)

> db.gitEvents.find({'type':{$in:["IssuesEvent"]}},{'payload.issue.user.login':1});

![screenshot](2c7.png?raw=true)

### 8 (4 points)

> db.gitEvents.find({'type':{$in:["IssuesEvent"]},'payload.action' :'closed'},{'payload.issue.id':1, 'payload.issue.state':1});

![screenshot](2c8.png?raw=true)

### 9 (4 points)

> db.gitEvents.find({'type':{$in:["IssuesEvent"]},'payload.issue.state' :'open'},{'payload.issue.user.login':1, 'payload.issue.state':1});

![screenshot](2c9.png?raw=true)

### 10 (4 points)

> db.gitEvents.find({'type':{$in:["IssuesEvent"]},'payload.issue.comments' :{$gt:0}},{'payload.issue.user.login':1, 'payload.issue.comments':1});

![screenshot](2c10.png?raw=true)


## Challenge 2 (8 points x 2 = 16 points) 

### 1 (8 points)

{question-in-plain-English}

> db.gitEvents.[complete this query]

![screenshot](22c1.png?raw=true)

### 2 (8 points)

{question-in-plain-English}

> db.gitEvents.[complete this query]

![screenshot](22c2.png?raw=true)
