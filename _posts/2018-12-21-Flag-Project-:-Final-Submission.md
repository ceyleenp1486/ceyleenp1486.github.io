---
layout: post
title: "Flag Project : Final Submission"
date: 2018-12-21
---

## Flag of Sweden by Ceyleen Paulino



## Describe your program
As I informed above, I designed the flag of Sweden using code. Based on the work I did I feel like in the end I'll receive a practitioner. Simply because I chose a fairly simple flag. While although I believe I completed decent work and tried my best I don't think I'm quite at professional level. There are still a few things I need to work on which will be later revealed further in my final submission.    


## Current output

* * *
![GitHub Logo](/images/sweden.png)
* * *


## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

Going back all the way to the beginning I stumbled upon my first challenge. I had a fairly easy time creating/programing the shapes needed for flag but there was one problem I had. Putting the shapes together and in the right placement. So I asked a few of my peers and I finally figured out one of the key factors for making this flag. A function called place-image that takes in an image, x-coordinate, you coordinate and another image. And just like that it I managed to put the shapes together with ease. Afterall, my flag only did involve just a large rectangle and two thin ones. However to my surprise I wasn't quite done just yet... Yes I did make my flag but that wasn't exactly what my professor wanted us learn from this "lesson". 


My professor wasn't fond of us numbers in our program. Simply because let's say you wanted to change your entire flag, you'd have to do it all individually. And that's not what he wanted us to take from this lesson since we'd be basically repeated what some of us did the last time we coded flags. He wanted us to code these functions to represent certain values that also have names in them. The only one function that should only hold a number value is size. Now thinking about it, size is sort of like a nucleus of a cell(based on its purpose in my coding). It controls everything else basically. The purpose of coding all these other functions is because my professor wanted to make the flag much more easier to change. Which presents this idea of abstraction. Abstraction is data thats simplified which basically represents the whole entire concept. One change to it and it'll change the entire outcome(s) of your coding. 

Hence I stumbled onto another major challenge when attempting to do what was requested. My challenge was using place-image without using numbers. At the time I was absoluetly confused, afterall how could values be words?? That's silly! So I requested assistance from the computer science professor. While although I made these other "short cuts" for other functions I had to continue repeating this process for the rest in order for my size function to be the abstraction of my entire code. So he properly introduced me to short cuts. 



<!--- Delete this comment and add your writing -->


## Explain your code.

-   Choose a significant part of your program (15 lines max) and paste it below. Do not insert your entire program here. _then delete this instruction_
-   Explain each argument in the code section. _then delete this instruction_
-   Tell us how it functions independently and within the whole program _then delete this instruction_

* * *

```
Insert 10-15 line code section here _then delete this instruction_
```

* * *

-   Explain the code you posted by telling us about each argument.
-   Then tell us how your code section fits into the whole.
 
<!--- Delete this comment and add your writing -->


## Program code

```
#-----------Sweden Flag 2.0-------

size = 20
width = size * 16
height = size * 10 


blueb = rectangle(width, height, "solid", "royal-blue")
#blueb is stort for "Blue background"
#blueb is supposed to be the blue part of flag 
#layer N.1

stripe1 = 5
s1w = width * 1/8
s1h = height 
#stripe-width = width * 1/8
#stripe1 is stripe1size 

vstripe = rectangle(s1w, height, "solid", "gold") 
#vstripe is short for vertical stripe
#vstripe is a rectangle that goes across the flag vertically 
#layer N.2
#vstripe has the same proportions of stripe1 
#vstripe = stripe1 EXCEPT vstripe is more specific on how the stripe should look

stripe2 = 5
s2w = stripe2 * 16
s2h = stripe2 * 2
stripe-height = height * 1/5

hstripe = rectangle(width, stripe-height, "solid", "gold") 
#hstripe is short for horizontal stripe!
#hstripe is a rectangle that goes across the flag horizontally
#layer N.3
#hstripe has the same proportions as stripe2
#hstripe = stripe2 but hstripe is more specific

#repeated-note ; place-image -> Image, X, Y, Image -> Image

vcross-x = width * 3/8
vcross-y = 100
#vcross-x is vstripe's x placement
#vcross-y is vstripe's y placement

bbsv = place-image(vstripe, vcross-x, vcross-y, blueb) 

hcross-x = 160
hcross-y = height * 1/2
#hcross-x is hstripe's x placement
#hcross-y is hstripe's y placement

swedenflag = place-image(hstripe, hcross-x, hcross-y, bbsv) 

#I still need to figure out how to change the size of my flag, without changing the flag design
#I need to figure out how to make the stripes scale down with the stripes

```
