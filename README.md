# 2468_SafeArea

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/2468_SafeArea/blob/main/2468_pro.PNG)

## What Algorithm should I use?

Graph Algorithm , dfs

## What was the key point and the hard part?

While getting the input, save the min value and max value of input to run faster(range limit).

After that , starting from the height min-1 to max , if that area's height is bigger than the height that we set, to dfs.

The reason why we have to start with min-1 is that maybe the input number is all same. In that case , max safe area will be 1 not 0. 

If we start from min not min-1, the answer of dfs will be 0.

After these sequence, find the max value of safe area will be the answer. 

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
