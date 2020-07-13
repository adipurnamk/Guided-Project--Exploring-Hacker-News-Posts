# Guided Project: Exploring Hacker News Posts
 Python for Data Science: Intermediate, Dataquest

---

![HN Logo](https://s3.amazonaws.com/dq-content/354/hacker_news.jpg)

In this project, we'll work with a data set of submissions to popular technology site Hacker News.

Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

You can find the data set here, but note that it has been reduced from almost 300,000 rows to approximately 20,000 rows by removing all submissions that did not receive any comments, and then randomly sampling from the remaining submissions. Below are descriptions of the columns:

>**id**: The unique identifier from Hacker News for the post  
**title**: The title of the post  
**url**: The URL that the posts links to, if it the post has a URL  
**num_points**: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes  
**num_comments**: The number of comments that were made on the post  
**author**: The username of the person who submitted the post  
**created_at**: The date and time at which the post was submitted

We're specifically interested in posts whose titles begin with either **Ask HN** or **Show HN**.  
We'll compare these two types of posts to determine the following:

* Do Ask HN or Show HN receive more comments on average?
* Do posts created at a certain time receive more comments on average?  
---


## Conclusion

If we refer back to the original dataset in [Kaggle](https://www.kaggle.com/hacker-news/hacker-news-posts), this dataset is based on Eastern Time in the US. If we live there, we should consider asking a question in Hacker News at 15:00. At that time is more possibility of the answer to be answered than the other time.  
Another time we should consider to post question is at 2:00, 20:00, 16:00, or 21:00

Since I lived in Western Indonesia (GMT+7), Eastern Daylight Time is 11 hours behind Western Indonesian Time. So, we add 11 hours to the recommended time.  
For Western Indonesian should consider posting a question at 2:00. Then 13:00, 19:00, 3:00, or 8:00.  
Maybe it's difficult for us to post at 2:00, it sleeping time actually, except for some of us who are nocturnal. The ideal time for usual people maybe after lunchtime at 13:00.