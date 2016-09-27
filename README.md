# Twitter stream API

This API is in charge of opening a stream connection with Twitter API, to track a #hashtag and emit tweet events throught web sockects technology

**Important**: The API works with the web component [polymer-twitter-realtimeline](https://github.com/polymer-day/polymerday-twitter-realtimeline)

## Install Node and npm

First, make sure you have the [Node JS](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed. 

## Config.json file

Create a [Twitter App](https://apps.twitter.com/), config it, get the necessary keys and tokens and put then in config.json file.

Instead config.json file, you can create the corresponding **Environment Variables** if you want

```json
{
    "consumer_secret": "your_consumer_secret",
    "consumer_key": "your_consumer_key",
    "token": "your_token",
    "token_secret": "your_secret"
}
```

## Server up and Running

```html
$ npm install
$ npm start
```
