
# "1010"

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![button](https://github.com/Choi-JaeHyeok-21500749/1010/blob/main/1010_pro.JPG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

1. There is only one option when N==M. 

2. If N is 1, answer is same as M.

Those 2 things are easy to find out.

After that, let's assume that we are adding a site.

(2,3)

N       M

o(N1)   o(M1)

o(N2)   o(M2)

        o(M3)
    
The upper one is the new one.
That case is same as

1. Match N1 and M1, and find the answer of (1,2)

2. Forget about newly added M(M1) and find the answer.

This are because we caanot build a bridge across. So if N1 does not select M1, there is no new options.

With this information, we can build a equation.


## Where can I get more help, if I need it?

You can contact me through email, which is 21500749@handong.edu.
Thank you for visiting this github!

