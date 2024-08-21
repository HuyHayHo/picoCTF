# [picoCTF 2019] - Insp3ct0r 

## Category: Web exploitation

## Difficulty: Easy

##  Description: Kishor Balan tipped us off that the following code may need inspection: `https://jupiter.challenges.picoctf.org/problem/41511/` [link](https://jupiter.challenges.picoctf.org/problem/41511/) or `http://jupiter.challenges.picoctf.org:41511`

## Hints
> 1. How do you inspect web code on a browser?
> 2. There's 3 parts

## Soltion

### Step 1: Visit the link
- We can see it is basic website with title, heading,...
- In the title `How` we can see how to make that site: HTML, CSS, Javascript
  
### Step 2: Analyzing the website
- Use `Developer tool` to check HTMl, CSS, Javascript exists on this page
- Visit FRAMES section in the Application and we will solve this exercise

## Flag
> picoCTF{tru3_d3t3ct1ve_0r_ju5t_lucky?832b0699}
## Conclusion
