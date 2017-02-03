# Spring 2017
# Project 1: What did the presidents say at their inauguation?

![image](figs/title.jpg)

### [Project Description](doc/)
This is the first and only *individual* (as opposed to *team*) this semester. 

Term: Spring 2017

+ Projec title: Exploring the relationship between focus of immigration in inauguration speeches and immigration statistics
+ This project is conducted by Kexin Nie
+ Project summary: 
   As we all have known, just few days after the inauguration ceremony of Donald Trump, the new executive orders for immigrants and refugees came out. Those policies has had a significant effect on everyone in this country. Many have been distressed and refused to accept the order. Trump’s negative attitude towards immigrants and refugees could be seen from some of his speeches last year, and he did come up with new orders against them. According to Trump’s new order, we might think whether the inauguration speeches reflect the trend of immigration policies, which might affect the immigration statistics. In this project, data mining techniques will be used to explore the relationship between inauguration speeches and immigration statistics.
  After finding word frequency and sentiment scores for immigration topic, we compare them to the change rate of yearly new immigrants numbers. After exploring the result plot, we notice sometime immigration statistics might have a positive relationship with sentiment scores and immigration word frequency. It might because a positive attitude and a lot focus on immigration during inauguration speech might reflect the president’s positive attitude towards immigration problem, which might affect his policies. But this claim is not always true since we observe some points in the plot against this claim. It might due to 1) There are many other factors which affect the immigration statistics other than immigration policies, such as economy and wars. 2) The random errors which happen in data mining process. Sentences that contain “immigration-related words” might not be immigration-related.
+ Methods:
 Import Speeches
 -Find immigration related words using term correlations
 -Compare the frequency of immigration related words in speeches To calculate the immigration-related words frequency
 -Analysis attitude of the speech through sentiment analysis
 -Compare the previous results to immigration statistics For immigration data
+ Tips for reproducing
 Make sure to put imm.csv in your working directory
 .You have to change the location of speech files in part 1 manually
 .In step0, if you fail to install certain packages, use romove.pakage(), then try to intall the package again
 
Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
