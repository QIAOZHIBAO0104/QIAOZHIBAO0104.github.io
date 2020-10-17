---
layout: post
title: Project2
---

This project has different challenging from the first one for me. I have very clear thoughts for what work should I do, so I finished the code part within a few hours. After that the real challenging came to me.

Firstly, I cannot fully understand the meaning and conception behind predictive variables as from correlation plots seems no obvious relationships between predictive variables and the response. I was confused with variable selection as there are a huge number of predictors which are weakly related with the response, so I just tried to remove some variables which are highly correlated with other predictive variables and some variables with variation 0.I was struggled with this since there is no certain rule for me to check the significance of variables.

Then I began to run my code trunk one by one, I got stuck in the model one part for some undetected reasons, though I already filtered the original data set by weekday. Later I found the filter way was not effective, I guess that was the reason. After fix that problem I easily run the whole code trunk within ten minutes, it looks like normal now. 
However, when it comes to automation of my report I was totally stuck with this. I back to the lecture video related automation to review, I was still confused with how to write the automation.Rmd. Honestly this really took me many hours to learn and summary good ideas from the discussion board. After I set the params, I found the data set need to be subset again, I cannot simply use ‘weekday_is_modeay==1’to filter, fortunately I found I can use the variable column==1 to replace. Anyway, I did make some modifications to make my code adapt automation process. 

When I was strolling in this project, just as I mentioned before it was struggling for me to select good variables to fit models since I thought there are certain criterion to help me get the most significant fit. But seconds ago an idea just occurred to me, that is maybe we don’t have to be so hard on selecting variables to fit models, there is no perfect selections but better always better model. So I guess this is the serendipity for me in project 2.
Please click [here](https://qiaozhibao0104.github.io/ST558-Project2/) to view my report.

