# CelebrityMatch


Here is how the api works
1. Both Twitter usernames (handles) are checked to make sure they're valid.
2. A call to the Twitter API retrieves the first 200 tweets from your Twitter feed (excluding any retweets).
3. A call to the Twitter API retrieves the first 200 tweets from the celebrity's Twitter feed (excluding retweets).
4. Your 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be analyzed.
5. The celebrity's 200 tweets are sent as a single body of text to the Watson Personality Insights (PI) API to be     analyzed.
6.The Watson PI API runs a sorting & matching algorithm to find the most common attributes between both bodies of text.
7.The application prints the results to the user.



 
