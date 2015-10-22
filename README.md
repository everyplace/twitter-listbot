Twitter Listbot
==================

This is a simple twitter bot, designed to retweet the contents of a twitter list.

This implementation tweets for [@StoriesInData](https://twitter.com/StoriesInData).

## Setup Your Own
1. [Create a twitter application](https://apps.twitter.com/app/new), grant it the necessary access, and generate your tokens/keys.
2. Deploy the bot to heroku with this easy deploy button: [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
3. After going through the automated app creation flow on Heroku, go to your app's settings (`https://dashboard.heroku.com/apps/<your app name here>/settings`) and create the following environmental variables:

### Environmental Varibles from your Twitter Application
* TWITTER_CONSUMER_KEY
* TWITTER_CONSUMER_SECRET
* TWITTER_ACCESS_TOKEN_KEY
* TWITTER_ACCESS_TOKEN_SECRET

### Custom variables for the account and lists you want to monitor
* TWITTER_ACCOUNT //StoriesInData for example
* TWITTER_LIST //data-driven-storytellers

For detailed setup instructions, see my blog post: [How to Set Up a Simple Javascript Twitter Bot](http://www.bryanbraun.com/2014/12/13/how-to-set-up-a-simple-javascript-twitter-bot)

## Credit
Twitter Listbot is written in [node.js](http://nodejs.org/) and based on [Sugendran](https://github.com/sugendran)'s [node-retweeter](https://github.com/sugendran/node-retweeter).
