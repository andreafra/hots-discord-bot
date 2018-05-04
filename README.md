# Discord 1337 Bot 🤖

A simple Discord bot that replies "damn it" whenever anyone says "1337"

![](https://cdn.glitch.com/f1b80a31-0733-40fb-a0dd-44c8c80c155d%2Fscreenshot.png?1506425519756)

## Prerequisites

You'll need:
 - A [Discord account](https://discordapp.com/register)
 - Permission to add accounts to a server, or your own server

## Steps to set up:

1. Create an App here: [https://discordapp.com/developers/applications/me](https://discordapp.com/developers/applications/me)
2. Create an App Bot User for your App by clicking "Create a Bot User"
3. Add the App Bot User to your Discord server using this link: `https://discordapp.com/oauth2/authorize?&client_id=441938351222685706&scope=bot&permissions=0` replacing `<CLIENT_ID>` with the Client ID found on the page of your App
4. Set the `DISCORD_BOT_ID` value in `.env` using the Bot User token ("click to reveal" in the App page under the bot username)

## The code

Check out `server.js` to see how it works ✨

We're using the [Eris](https://npm.im/eris) library to interact with the Discord API.

If it's working you should see "Ready!" in the logs.