# Analyzing Trump’s Twitter Compulsion


I copied Trump’s tweet data from the Trump Twitter Archive, opting to analyze the tweets starting on Jan. 20, 2017 at the top of his Presidential term. After saving the text data as a csv file, I imported the file into a Jupyter Notebook using the Pandas library.

As a data science student at the Flatiron School, I have been studying statistical distributions and probability. The Poisson Distribution is interesting because it allows us to calculate the probability of a given event happening by examining the average number of events that happen in a specific time frame. 

Given that it is currently a Tuesday in 2019, he is averaging around 12 tweets a day and he reports to only sleep about 5 hrs a day, the probability is pretty low — at 11%.

![by_hr](https://user-images.githubusercontent.com/54602329/68094976-87875c00-fe73-11e9-95c1-fbe33257246e.png)

![wk](https://user-images.githubusercontent.com/54602329/68095150-016c1500-fe75-11e9-9d56-81b34e73c5cd.png)

I downloaded a copy of Trump’s leaked private schedule from Axios and converted it into a csv file, I then merged the file with his tweet data. We can now see what Trump was supposed to be doing and where he was located while tweeting- November 7, 2018, through February 1, 2019. It looks like the majority (166 tweets) were sent while he was scheduled to be in the Oval Office.

![sched](https://user-images.githubusercontent.com/54602329/68095070-83a80980-fe74-11e9-876d-7e324ab6fa74.png)


More on this at https://towardsdatascience.com/analyzing-trumps-twitter-compulsion-3c6a61ba8354
