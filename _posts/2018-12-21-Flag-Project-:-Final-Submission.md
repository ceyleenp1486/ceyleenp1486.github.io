---
layout: post
title: "Flag Project : Final Submission"
date: 2018-12-21
---

## Flag of Sweden by Ceyleen Paulino

## Describe your program

-   What country did you design for? _then delete this instruction_
-   What grade do you expect? _then delete this instruction_

<!--- Delete this comment and add your writing -->

## Current output

* * *
![GitHub Logo](/images/sweden.png)
* * *

## Describe your process.

-   What questions, strategies, help from peers or teacher, or thinking got you to this point? _then delete this instruction_

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
