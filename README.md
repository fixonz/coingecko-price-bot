# Coingecko Price bot

A Discord bot that fetches and shows token data from Coingecko.
Open in Autocode
================

To add an Open in Autocode button to your GitHub repository,
simply copy and paste the following code anywhere into README.md

[<img  data-src="https://deploy.stdlib.com/static/images/deploy.svg" width="192">](https://open.autocode.com/)

Enjoy!
  - Standard Library Team
  - 
## Quickstart

<a href="https://heroku.com/deploy?template=https://github.com/imdipul/coingecko-price-bot">
<img src="https://www.herokucdn.com/deploy/button.svg" alt="Deploy">
</a>

Click here to deploy!

## Developer quick start 👩‍💻

`npm run dev` will launch the bot locally, with hot reloading included.

There are a few other scripts provided:

- `start`: Starts up the bot without hot reloading; used for the Heroku deployment.

### Configuration 🔧

First, install the dependencies:
`npm install`
`npm install -D`

For the bot to run, it needs these variables, laid out in the `.env.sample` file:

- `DISCORD_API_TOKEN`: Your discord API token. [See this guide on how to obtain one](https://github.com/reactiflux/discord-irc/wiki/Creating-a-discord-bot-&-getting-a-token).
- `TOKEN_ID`: Your token ID on CoinGecko. (The identifier on the CoinGecko URL of your token).

by imdipul
