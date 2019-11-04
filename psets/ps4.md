# Problem Set 4 (out of 120 points)

# Problem 1 (20 points)

* Github classroom link: https://classroom.github.com/a/G8PbWTDW

As we've read in class, people reuse passwords across accounts. As a result, [password breaches](https://www.troyhunt.com/the-legitimisation-of-have-i-been-pwned/) cause major security issues in many cases. For this problem, imagine that you are in charge of IT Security at GW, and that Facebook recently suffered a major password breach. You find plaintext passwords from Facebook on the dark web, and some of the usernames and passwords in that leaked data are the same (or similar to) username-password pairs at GW. Follow the NEAT and SPRUCE guidelines to craft a notification to potentially impacted UChicago users. 

In the github submission, include a file called `answer.md` with the following information:

1. One paragraph describing what details you believe to be most important to communicate, and why.

2. One paragraph describing the decisions you made in designing your breach notification grounded in the NEAT and SPRUCE guidelines discussed in class.

3. A sentence or two describing how this notification will be distributed (over email? etc.) and to whom.

Also include a file called `mockup.pdf` (or `mockup.png` or `mockup.jpg` or etc.) that is an actual mock-up of the breach notification itself. (Make sure it looks nice.)


# Problem 2 (30 points)

* Github classroom link: https://classroom.github.com/a/DioTrR_M

We've been discussing different privacy notices and how privacy and data processing is communicated to end users. For this assignment, you are going to review common privacy notices. Read the following privacy policies for popular services:

* [Wikimedia](https://foundation.wikimedia.org/wiki/Privacy_policy)
* [Reddit](https://www.reddit.com/wiki/privacypolicy)
* [Twitch](https://www.twitch.tv/p/legal/privacy-notice/)
* [New York Times](https://help.nytimes.com/hc/en-us/articles/115014892108-Privacy-policy)

You should submit two files:

* `analysis.md`: 
 * Write one paragraph describing the general readability and accessibility of these privacy policies. Can it be improved? What is understandable and what is not?
 * Write one paragraph on similarities in these privacy policies, particularly regarding data process and how data is used.
 * Write one paragraph describing any differences between these privacy policies. Can you account for why there may be differences?
 
* `faq.md`:
 * Create a FAQ (Frequently Asked Questions) list based on these privacy policies for advice on reading privacy policies, generally.
 * You should include at least 5 questions and answers, and each answer should be about one paragraph in length.


# Problem 3 (60 points)

* Github classroom link: https://classroom.github.com/a/gt8q9slu

Twitter provides an [API to collect data posted on Twitter](https://developer.twitter.com/en/docs/tweets/filter-realtime/overview). The Twitter API allows you to get a real-time, random sample of all tweets containing a set of keywords being posted on Twitter.

Utilize the Twitter API to collect all the tweets that was posted about information security and information privacy in real time for 8 hours. Note that you need to [create a Twitter developer account](https://www.slickremix.com/docs/how-to-get-api-keys-and-tokens-for-twitter/) for the data collection. You will have to choose your keywords carefully so that you obtain sufficiently relevant data from the API. Write code to filter out non-English tweets from your collection. 

Create a [word cloud from the filtered text of your tweets after removing all stop words](https://www.wordclouds.com/), punctuation, and user mentions (tokens starting with "@").

Finally, it would be nice to know what are the most prominent information security and privacy concerns that Twitter users talked about during your data collection. To that end, randomly sample 50 English tweets from your collected set and manually divide them into at most 6 thematic categories representing information privacy and security issues. That is, you should conduct a inductive coding of the tweets and report on the 6 most dominate codes you observe. 

Turn in the following in your github classroom link:

1. All code you wrote (which can be in any programming language). Be sure to name these files reasonably. Your code should take in a file called `search_terms.txt` for which keywords to look up. You should also submit the `search_terms.txt` file.
2. A file called `wordcloud.jpg` (or `.png` or whatever) that contains hyour word cloud.
3. A file called `topten.txt` that contains the top ten keyworkds from your wordcloud. 
4. Turn in a file called `coding.pdf` that contains a table describing the thematic categories you manually created, the number of tweets (out of 50) in each theme, and an example tweet for each.
5. A file called `report.pdf` that contains a report of your work on this part of the project, as well as a discussion and interpreation of your thematic coding, similar to what we've seen in the papers we've read. 


# Problem 4 (10 points)

* Github classroom link: https://classroom.github.com/a/j8TVdlKG

Write a first draft of the methodology section for your class project. This should be organized similar to the papers you've read in class. Include details on how your survey instruments were developed, and other clarifying information. In your github submission this should be called `methods.pdf` 

Additionally, you should include exact questions, survey scripts in your submission as separate files. These files should be named appropriately, and you can refer to them directly from your `methods.pdf` if need be. 

