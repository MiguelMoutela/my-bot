# My Bot

A very simple example bot using the Microsoft Bot Framework

## Prerequisites

* Node.js
* A [Microsoft Bot Framework](https://dev.botframework.com) / Azure account
* [Microsoft Bot Framework emulator](https://docs.microsoft.com/en-us/bot-framework/bot-service-debug-emulator)

## Setup

### Create a new bot

* Create a new bot at https://dev.botframework.com/bots/new
* Create an App Name, ID and password (copy to clipboard)

### Add your credentials

* Create a file called .env in the root of your project
* Customise and Add the following to your .env file

```
MICROSOFT_BOT_APP_PASSWORD=[PASSWORD]
MICROSOFT_BOT_APP_ID=[YOUR_BOT_ID]
MICROSOFT_BOT_APP_NAME=[YOUR_BOT_NAME]
```

### Install dependencies:

```
yarn install
```

### Start the bot:

```
yarn start
```

### Access the bot

Run the bot framework emulator, add the url and credentials and hit 'Connect'

![](https://cdn-images-1.medium.com/max/1600/1*OX97aCFuDfCWAx8oKMdenA.png)

### Start chatting!

## Tests

Run the tests by running:

```
npm test
```
