# Bias Detection by Subreddit

The project is currently a WIP but the idea is to allow the extraction of bias information from subreddits through the use of word embeddings.

Purpose is two fold:
1. Direct data interpretation.

A rough example:
The numbers correspond to their bias in favor of either topic, either right above or below. The a positive number corresponds to a bias towards the topic up top, a negative numnber corresponds to a bias towards the topic below. A 0 result shows no bias between topics.
So for the first column which dictates the bias between Flowers/Insects, all subreddits are biased towards flowers. www.reddit.com/r/onguardforthee had the least biased result with a value of 0.4.
![Rough Example](https://i.imgur.com/G79XP8r.png)

2. To be used in a further model as features. Which I plan to do once this project is complete.
