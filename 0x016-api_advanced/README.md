This project contains more tasks for learning how to consume RESTful APIs.
Tasks To Complete

    0. How many subs?
    0-subs.py contains a Python function queries the Reddit API and returns the number of subscribers (not active users, total subscribers) for a given subreddit. If an invalid subreddit is given, the function should return 0.
        Hint: No authentication is necessary for most features of the Reddit API. If you’re getting errors related to Too Many Requests, ensure you’re setting a custom User-Agent.
        1. Top Ten
1-top_ten.py contains a Python function queries the Reddit API and prints the titles of the first 10 hot posts listed for a given subreddit.

2. Recurse it!
2-recurse.py contains a recursive Python function that queries the Reddit API and returns a list containing the titles of all hot articles for a given subreddit. If no results are found for the given subreddit, the function should return None.

3. Count it!
100-count.py contains a recursive Python function that queries the Reddit API, parses the title of all hot articles, and prints a sorted count of given keywords (case-insensitive, delimited by spaces. Javascript should count as javascript, but java should not).

   To make life easier, java. or java! or java_ should not count as java.
If no posts match or the subreddit is invalid, print nothing.
NOTE: Invalid subreddits may return a redirect to search results. Ensure that you are NOT following redirects.
Your code will NOT pass if you are using a loop and not recursively calling the function! This /can/ be done with a loop but the point is to use a recursive function. :)
