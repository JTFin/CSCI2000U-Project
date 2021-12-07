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

![GraphQ1](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q1-g1.PNG?raw=true)

Looking to confirm those findings, we took to this graph and eliminated the extreme outliers for readability. The observations are now much clearer. While episodes do have a better rating the longer they run technically, it is because of the sheer amount of tv series sitting at around 20 episodes and low ratings that brings the score down. Looking past that we see what we sought out to find... episode count does infact lead to a low declining score over time.

---

While analyzing the data, we found correlation between the amount each genre is released every year, and the ratings and number of votes. The total overall ratings of a genre, as well as the number of votes, may have an influence over the how often a piece of media in a specific genre is released. 

When comparing the data showing the number of releases per genre every year with the number of ratings and votes a genre got, we can see a pattern emerging. Whenever a genre has a high overall rating one year, there is an increase in the number of times published in the following years. The opposite is true as well. If a genre has low ratings, less of that genre will be released. The same can be said for the number of votes each genre gets every year. Genres that see a decline in production are the ones who see a drop in the number of votes. Meanwhile, those with higher votes see an incline. 

![GraphQ2a](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q2-g1.png?raw=true)
![GraphQ2b](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q2-g2.png?raw=true)
![GraphQ2c](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q2-g3.png?raw=true)

We can see that the number of ratings and votes can be used to predict the performance of a genre in the upcoming years.

---

![GraphQ3a](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q3-g1.PNG?raw=true)
![GraphQ3b](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q3-g2.PNG?raw=true)

The graph displays the main findings from the computations. After analyzing the data, it is clear that if you were to make an outline of the data, you would get a shape that resembles a parabola. When considering a parabola, one of the main aspects of it is it's symmetry. Although this graph clearly is not perfectly symmetrical, something that can be backed up by the slope calculations that were performed, it is very close, and that is all that's needed based on the data we're working with. 

How so? Well, to briefly go over the three main sections of the data, it goes from a downwards trend, to straight, and then upwards. This partial symmetry, in the context of the data we're comparing, would imply that as rate increases, the amount of mature content can increase or decrease, with a little area in between where there are no changes between the two datasets. 

Clearly, this doesn't make sense in the end and it leads to a clear conclusion to the original research question.

---

When looking at how films performed when compared to series, we found that films scored overall worse than series. This however was likely due to sampling, as the number of films more than doubles the number of series. The difference in scores also only becomes noticeable as the difference in films vs series produced increases, and at around the same time period. 

![GraphQ4a](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q4-g1.png?raw=true)
![GraphQ4b](https://github.com/JTFin/CSCI2000U-Project/blob/main/Images/Q4-g2.png?raw=true)

Had the number of series been larger, it too likely would have been brought down to a more middling score, just as a result of having more middling series.

## Conclusion

### Reflection
In the duration of this project and working with the data provided, as well as our own analysis, we were able to answer our initial questions and learn from it. Ratings played the biggest role in understanding how the data flows year by year. We confirmed that ratings drop as the length of a series extends, and ratings on a genre often play a role in how frequently that genre is present in the following years. 

When making a comparison with films to series, the rating of a series is often significantly better than a film, which could be a result of bias or sheer number of films present.

Lastly when trying to identify how mature content effects the general rating of a series or movie... it does not seem to at all. Anecdotally, this makes sense, as edgy films have always been present in media, and more often then not, sticking to the source material whether it has mature content or not is often preferred. 

### Refinement
There could be a number of improvements made to this project. First of all, the source data integrity could be much better, as we found easily observable problems (i.e., incorrect dating, duplicate records) that could be fixed before processing. Additionally, a sub-dataset could be utilized specifically for series, and ratings throughout the seasons, instead of as a whole.

If we were to make changes in the future, we could include a subset for actors, and line it up with all rows present, and see how a specific actor effects the ratings, episode count, mature content, etc... This could add a lot more interesting datapoints which could prove useful.

## Acknowledgements
This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.

## README
1. Install WSL if on windows
2. Install docker
3. Install jupyter notebooks
4. Download & extract files into a directory recognized by jupyter notebooks
5. Run with *sudo docker-compose up --build* with command line
6. Open the given local url, and navigate to the notebook
