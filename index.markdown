---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout : default
---

Rumor has it that people spend more time on social media during holidays. Does this fact apply to Twitter? Companies certainly don’t miss the occasion for advertising their products. So how many people are in danger of seeing something they really want to buy and almost definitely don’t need? Let’s look at the data. 

{% include allTweets.html %}

In order to reduce the noise of the initial twitter data we decide to group all tweets by week across all years (2006 - 2014) and normalize it using the amount of active egos per week. The two following plots show the weekly average tweet per user count and the number of active unique users per week.

{% include story.html %}

Initially, we were thinking of looking at the average number of tweets during a specific holiday week such as Christmas or Thanksgiving and compare it with the average number. However when including all countries this analytical task becomes hard to interpret, as it seems like the majority of users are most active during the summer and fall. 
Therefore, we decided to look closer at each individual country to see if we could gain some insight using country specific holidays (i.e. American tweeters and Thanksgiving.).

{% include filename.html %}

{% include tweet.html %}

