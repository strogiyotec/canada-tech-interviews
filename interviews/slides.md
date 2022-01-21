---
layout: center
class: 'text-white'
---
# Technical Interviews in Canada
### (My experience)

---
layout: center
class: 'text-white'
---

## whoami ? 
<style type="text/css">
    img {
        width: 250px;
    }
</style>
![Me](index.jpeg)

1. Seniour Networking Engeneer in Relic Entertainment
2. Java/Linux/Dabases enthusiast
3. Open source lover
4. <logos-Blogger/> **Blog** - https://strogiyotec.github.io/
5. <logos-git/> **Github** - https://github.com/strogiyotec
6. <logos-telegram/> **Telegram** - @Lollipopster


The following is intended to outline my personal experience. It is intended
for information purposes only, and may not be incorporated into any contract. It
is not a commitment to deliver any material, code, or functionality, and should
not be relied upon in making final decisions. Relic Entertainment information remains at the sole discretion of Relic.

---
layout: center
class: 'text-white'
---
# Motivation 1. Interviews in North America are a little bit different
2. Different companies have different policies
3. Just share my experience
   
---
layout: center
class: 'text-white'
---
## Agenda
1. Interviews overview
2. Negotiations
3. How Did I prepare and some resources(Linkedin)
4. Personal hints

---
layout: center
class: 'text-white'
---
# Some numbers
1. Applied to 59 companies
2. 15 rejections without having an interview
3. 15 rejections after having an interview
4. 5 companies just stopped responding to my messages
5. 4 job offers 
   

---
layout: center
class: 'text-white'
---
# Let's start 
## The size is actually matters 
1. Startups
2. Medium size companies or big non technical companies
3. Big tech companies

---
layout: center
class: 'text-white'
---
# Startups - 4 companies
 
---
layout: center
class: 'text-white'
---
## What they ask ? 
1. Two rounds(technical , with SEO)
2. Language they use(java,js,python etc.)
3. Framework they use(Spring,express,Django etc.)
4. Database they use(Postgres,Mysql)
5. Technical assignment
6. Previous experience if any

---
layout: center
class: 'text-white'
---
## Whay they don't ask ? 
1. Behavioural questions(how do you handle stress)
2. Algorithm based questions( Invert binary tree, reverse linked list )

---
layout: center
class: 'text-white'
---
# Medium size companies - 15


---
layout: center
class: 'text-white'
---
## What they ask ? 
1. Multiple interview rounds
2. Language(most of the time without the framework)
3. Live coding(algorithms, find a bug in a given source code)
4. The knowledge of the standart library
    1. Given a line `1-2-33-43-12` sum up all the ints
    2. You need an ordered key value storage
    3. Read the content of the file
5. Backend related stuff
    1. SQL(`table user(id,name,manager_id,salary,company)` top 3 salaries by company for users without managers)
    2. User sends a payment request and your backend has been restarted
    3. Cloud and Linux


---
layout: center
class: 'text-white'
---

# What they don't ask ? 
1. Behavioural questions
2. Leetcode based questions

---
layout: center
class: 'text-white'
---
# Some hints
1. Check the company's product(register, send few requests, propose some additions)
2. Tell us about yourself(my favorite question)
    1. Java virtual machine(show that you know the runtime of a language you are working with)
    2. Garbage collectors(ask which garbage collector they use and why)
    3. Databases(tell them how tables are stored on disk)
    4. Linux

---
layout: center
class: 'text-white'
---
# Big tech companies
1. Amazon
2. Yelp
3. Dropbox
4. Grammarly

---
layout: center
class: 'text-white'
---
# The process
1. Technical assignment(they just copy paste easy leetcode questions)
2. Main interview(3-4 rounds)
    1. Behavioural questions
    2. Leetcode questions(medium/hard)

---
layout: center
class: 'text-white'
---
## Amazon
1. 4 rounds(3 leetcode questions, 8 behavioural questions)
2. Leetcode questions same as shown in premium subscription
3. System design(notification system, instagram, Youtube)

---
layout: center
class: 'text-white'
---
## Yelp
1. 4 rounds(1 round behavioural questions, 3 rounds coding style questions)
2. `You have a class Business, implement a method that fetches top 3 businesses by revenue`

---
layout: center
class: 'text-white'
---

# During the interview
1. Use a browser based text editor
2. Google meeting or similar software for a call

---
layout: center
class: 'text-white'
---
# What I didn't like about big tech companies
1. Nobody cared about me as a person
2. Every interviewer was a way too serious(making joks didn't help)
3. Interviewers didn't want to go out of the scope of given questions


---
layout: center
class: 'text-white'
---
# Once you have an offer - Negotiations
1. Something I was not familiar with
2. Always negotiate(because companies always lower your expected salary)
3. Stock options / Restricted Stock Units

---
layout: center
class: 'text-white'
---
# Preparation

---
layout: center
class: 'text-white'
---
# Where to apply ? Linkedin
1. Job search
2. Write to HR
3. Find a company's website and apply there

---
layout: center
class: 'text-white'
---
# How to prepare
1. Algorithms and data structures
2. System design
3. Behavioural questions(I failed here so don't trust me)
4. And of course your language of choice

---
layout: center
class: 'text-white'
---
# Algorithms and datastructures
1. Leetcode(google Top 100 Leetcode questions and then filter by company prior to the interview)
2. Introduction to Algorithms -  Thomas H. Cormen

---
layout: center
class: 'text-white'
---
# System design
## System Design Interview – An Insider's Guide

---
layout: center
class: 'text-white'
---
# Behavioural questions
I just googled the way people usually respond and did the opposite 

---
layout: center
class: 'text-white'
---
# Your language of choice
1. Learn the standart library(use languages with build in datastructures, Got it Golang ?)
2. Learn how to deploy the app written in your language to remote server
3. Pitfalls of your language

---
layout: center
class: 'text-white'
---
## Hints
1. Don't spend more than an hour on Leetcode questions, it doesn't worth it
2. Lost your motivation ? Go back to easy questions
3. Repeat already solved problems
4. Try not to use editor unless you stuck and need a debugger
5. For not big tech , learn how to write tests

---
layout: center
class: 'text-white'
---
# Let's solve one problem shall we? 
Given an array of distinct integers arr, 
find all pairs of elements with the minimum absolute difference of any two elements.

```
Input: arr = [4,2,1,3]
Output: [[1,2],[2,3],[3,4]]
Explanation: The minimum absolute difference is 1. 
List all pairs with difference equal to 1 in ascending order.
```

---
layout: center
class: 'text-white'
---
# Method body
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
        
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    //Let's sort
    Arrays.sort(arr)//O(nLogn)
    //1,3,6,10,15
    
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    Arrays.sort(arr)
    //Need to store a min difference
    //and a list of pairs
    int minDiff = Integer.MAX_VALUE;
    List<Tuples> list = new ArrayList<>();
    for(int i =1;i<arr.length;i++){
       int currentDiff = arr[i]-arr[i-1];
       if(currentDiff < minDiff){
            minDiff = currentDiff;
            //if input was 1,3,6,[10,11]
            list.clear();
            list.add(new Tuple(arr[i],arr[i-1]));
       } else if(currentDiff == minDiff){
            list.add(new Tuple(arr[i],arr[i-1]));
       }
    }
    for(Tuple tuple: list){
        System.out.println(tuple);
    }
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    Arrays.sort(arr)
    //Need to store a min difference
    //and a list of pairs
    int minDiff = Integer.MAX_VALUE;
    List<Tuples> list = new ArrayList<>();
    for(int i =1;i<arr.length;i++){
       int currentDiff = arr[i]-arr[i-1];
       if(currentDiff < minDiff){
            minDiff = currentDiff;
            list.clear();//this is bad O(n)
            list.add(new Tuple(arr[i],arr[i-1]));
       } else if(currentDiff == minDiff){
            list.add(new Tuple(arr[i],arr[i-1]));
       }
    }
    for(Tuple tuple: list){
        System.out.println(tuple);
    }
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    Arrays.sort(arr)
    //Need to store a min difference
    //and a list of pairs
    int minDiff = Integer.MAX_VALUE;
    List<Tuples> list = new ArrayList<>();
    int tupleStartIndex = 0;
    for(int i =1;i<arr.length;i++){
       int currentDiff = arr[i]-arr[i-1];
       if(currentDiff < minDiff){
            minDiff = currentDiff;
            list.add(new Tuple(arr[i],arr[i-1]));
            tupleStartIndex=i;
       } else if(currentDiff == minDiff){
            list.add(new Tuple(arr[i],arr[i-1]));
       }
    }
    for(int i = tupleStartIndex;i<list.size();i++){
        System.out.println(tuple);
    }
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    Arrays.sort(arr)
    //Need to store a min difference
    //and a list of pairs
    int minDiff = Integer.MAX_VALUE;
    List<Tuples> list = new ArrayList<>();
    int tupleStartIndex = 0;
    for(int i =1;i<arr.length;i++){
       int currentDiff = arr[i]-arr[i-1];
       if(currentDiff < minDiff){
            minDiff = currentDiff;
            list.add(new Tuple(arr[i],arr[i-1]));
            tupleStartIndex=i;
       } else if(currentDiff == minDiff){
            list.add(new Tuple(arr[i],arr[i-1]));
       }
    }
    for(int i = tupleStartIndex;i<list.size();i++){
       //IO is expensive
        System.out.println(list.get(i));
    }
 }
```

---
layout: center
class: 'text-white'
---
```java
 //15,1,3,10,6
 public void minimumAbsDifference(int[] arr) {
    Arrays.sort(arr)
    //Need to store a min difference
    //and a list of pairs
    int minDiff = Integer.MAX_VALUE;
    List<Tuples> list = new ArrayList<>();
    int tupleStartIndex = 0;
    for(int i =1;i<arr.length;i++){
       int currentDiff = arr[i]-arr[i-1];
       if(currentDiff < minDiff){
            minDiff = currentDiff;
            list.add(new Tuple(arr[i],arr[i-1]));
            tupleStartIndex=i;
       } else if(currentDiff == minDiff){
            list.add(new Tuple(arr[i],arr[i-1]));
       }
    }
    final StringBuilder builder=  new StringBuilder();
    for(int i = tupleStartIndex;i<list.size();i++){
            builder.append(list.get(i)).append("\n");
    }
    System.out.println(builder.toString());//IO happens only once
 }
```

---
layout: center
class: 'text-white'
---
## What was the point ? 
1. Check your time complexity analyses
2. Usage of build in classes
3. Computer science knowledge

---
layout: center
class: 'text-white'
---
# Thank you for attention
