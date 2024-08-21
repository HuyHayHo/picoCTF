# [picoCTF 2019] - where are the robots

## Category: Web exloitation

## Difficulty: Easy

##  Description: Can you find the robots? `https://jupiter.challenges.picoctf.org/problem/36474/` [link](https://jupiter.challenges.picoctf.org/problem/36474/) or http://jupiter.challenges.picoctf.org:36474

## Hints
> What part of the website could tell you where the creator doesn't want you to look?

## Soltion

### Step 1: Visit the link

### Step 2: Find robots.txt
- In Url of website, add 'robots.txt'
  
    ![alt text](image/image12.png) 

- Then copy value of Disallow and paste to the URL
  
## Flag
> picoCTF{ca1cu1at1ng_Mach1n3s_477ce}
## Conclusion
To solve the challenge, access the robots.txt file of the website by appending robots.txt to the URL. This file indicates areas that the website creator prefers to be hidden from search engines, which may contain the flag. Extract the disallowed paths from robots.txt and use them to find the flag.