# CelebrityMatch


Here is how it works
1. Both Twitter usernames (handles) are checked to make sure they're valid.
2. A call to the Twitter API retrieves the first 200 tweets from your Twitter feed (excluding any retweets).
3. A call to the Twitter API retrieves the first 200 tweets from the celebrity's Twitter feed (excluding retweets).
4. Your 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be analyzed.
5. The celebrity's 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be     analyzed.
6.The Watson PI API runs a sorting & matching algorithm to find the most common attributes between both bodies of text.
7.The application prints the results to the user.


The application does the following:

1.Accepts two Twitter usernames as variables.

2.Retrieves the last 200 Tweets from each Twitter username.

3.Sends the text of the 200 Tweets to the Personality Insights (PI) API  to gain insights on the two users.

4.Compares the users to one another.

5.Displays the results of the comparison.


The final results displayed will be the top 5 traits shared between the two Twitter users (for example: you and a celebrity of your choice).
 
