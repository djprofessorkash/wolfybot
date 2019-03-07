## Proposal:
### A Slackbot that can effectively serve as a quick Googler for questions and answers.

***

_The Problem_:

> When it comes to finding the answer to a quick math question or looking up a quick fact, many students turn to Google or other search engines. However, the distractability rate of a standard Internet browser is relatively high. 

> **Wouldn't it be great to have a bot within Slack that could look up your questions for you?**

_The Solution_:

> **MathyBot** is a Slackbot that utilizes a comprehensive search engine database and a natural-language processing package to directly receive user questions in Slack and immediately respond with top relevant answers across the Internet. 

> In particular, **MathyBot** uses _Wit.ai_ to tokenize and isolate the key characteristics of a user's question. **MathyBot** then sends that data to the _Wolfram Alpha_ database and receives filtered answers across the web that is then curated and returned to the user.

_The Action Plan_:

* ~~Connect **MathyBot** to the Slack API.~~
* ~~Successfully integrate with Make School's Slack.~~
* ~~Accept a question from a user.~~
* ~~Send the same user a static response following a question.~~
* ~~Connect **MathyBot** to the _Wit.ai_ API.~~
* ~~Break down user questions into tokens based on relevance.~~
* ~~Set confidence level to prioritize most relevant tokens for question responsivity.~~
* Connect **MathyBot** to the _Wolfram Alpha_ API.
* Send tokenized user question to the _Wolfram Alpha_ database.
* Grab relevant responses and return to user.