# Fool
Fool is an auto catcher/spammer for Pokemon Discord Bots 

This is not a self-bot, so you dont have to worry about being banned from Discord. Use at your own risk anyway.

Note: Currently only works for Poke Gal, will add Mewbot and Poketwo.

## Prerequisites
You need Windows 10 installed. This has not been tested with macOS or Linux.

You need to have Node.JS ^13.10.1, NPM ^6.13.7, & Python ^3.5.7 installed.

You should have a private Discord server ready to use.

## Getting Started

1. Go to the Discord Developers Portal and create a new app. Go to the bot tab and tick 'Add Bot'
2. Get the invite link to your bot (under the oAuth2 tab) and invite it to your private server
3. Go back to the bot tab and copy the token.
4. Download and extract the latest release from this repository (v2.0.0-beta).
5. Open `config/options.json`.

5.a Change the field `"foolToken"` to the token you copied earlier.

5.b [Optional] Change the field `"prefix"` to the prefix you would like to trigger THIS bot with.

5.c [Optional] Change the field `"userId"` to your Discord ID. To get this info, enable Developer Mode in appearance settings and right click your name.

5.c [Optional] Change the field `"interval"` to the interval you want the bot to spam at (in ms).

### We're almost ready to run the bot!
6. Open the terminal in the folder that Fool is in.

6.a Run the command `npm i` and wait for all the dependencies to be installed.

6.b Run the command `node .` and the bot will start running.

7. Enjoy and catch em' all!

# Troubleshooting

If it's not autocatching and only spamming, check to see if the bot is offline. If it is offline, follow the steps below. If it's online, let me know (through issues or [discord](https://discord.gg/TfeMbKu)) as it's likely due to updated images.

If it logs an error saying you have an invalid token, you probably have malformed JSON formatting.
I suggest you take a look at [this](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) to get a better grasp of how its supposed to be formatted.

These are the only known problems people have had. If your're getting something other than that, please create an issue describing it or tell us about it in the [discord server](https://discord.gg/TfeMbKu). Please provide screenshots of your CLI (command prompt)
