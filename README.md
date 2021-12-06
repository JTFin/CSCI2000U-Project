# What it means to be in IMDB's most popular list

## About us
We are group 29, with the following members:

Ashar Izhar -> https://github.com/Ash3223

Bridget Green -> https://github.com/Bridget-Green

Cameron Millar -> https://github.com/Cameron-Millar

Julian Finley -> https://github.com/JTFin

## Introduction
The topic you will be reading is about the aformentioned IMDB's most popular list of films and series(shows). This dataset was chosen as the topic we would cover as it contains a rich amount of entries, and many different category types to consider, which will make it much easier to perform the exploratory data analysis(EDA) phase of this project. Most importantly; due to the interesting and entertaining nature of movies and series, everyone was more than comfortable with working with this specific dataset, and digging deep into why points in the data, are the way they are.

If you are a film or tv lover, and always wondered why movies haven't been great in recent years, or why your favourite show got worse as it went on; this may be the report for you!

## Discussion
When analysing the amount of episodes present in any given tv series, we tried to see if there was any relation between how popular it was, and how many episodes there were. Right away, it was interesting to discover there were some series that infact not only had over 1,000 episodes, but 10,000 episodes! While clearly this is not the norm for regular television, we had to take into consideration how those types would effect how we went through our analysis.

At the bottom of that list, some tv series had as little as 3 or 4 episodes... were they cancelled shows, or intentionally had small runs? It is a puzzling metric.

Going into the meat of the question, when trying to find out if there was a ratings to episodes correlation. We took the top and bottom chunks of data and gave a comparison in the average rating and found that the higher amount of episodes has a higher rating.

![GraphQ1](https://github.com/JTFin/CSCI2000U-Project/blob/main/Stuff/Q1-g1.PNG?raw=true)

Looking to confirm those findings, we took to this graph and eliminated the extreme outliers for readability. The observations are now much clearer. While episodes do have a better rating the longer they run technically, it is because of the sheer amount of tv series sitting at around 20 episodes and low ratings that brings the score down. Looking past that we see what we sought out to find... episode count does infact lead to a low declining score over time.


![image](https://user-images.githubusercontent.com/90144034/144937174-5cd5e42a-6e6f-47f4-9aa5-659bf8dd1853.png)
![image](https://user-images.githubusercontent.com/90144034/144937197-e63d0fae-6698-4b20-9143-717d85b69dfb.png)
![image](https://user-images.githubusercontent.com/90144034/144937220-bfcdc9a0-cac7-43f1-9fa0-78b825e3ebfe.png)


While analyzing the data, we found correlation between the amount each genre is released every year, and the ratings and number of votes. The total overall ratings of a genre, as well as the number of votes, may have an influence over the how often a piece of media in a specific genre is released. When comparing the data showing the number of releases per genre every year with the number of ratings and votes a genre got, we can see a pattern emerging. Whenever a genre has a high overall rating one year, there is an increase in the number of times published in the following years. The opposite is true as well. If a genre has low ratings, less of that genre will be released. The same can be said for the number of votes each genre gets every year. Genres that see a decline in production are the ones who see a drop in the number of votes. Meanwhile, those with higher votes see an incline. We can see that the number of ratings and votes can be used to predict the performance of a genre in the upcoming years.

## Conclusion

## Acknowledgements
This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.

## README
