# Fool
Fool is an auto catcher/spammer for Pokemon Discord Bots 
Note: Currently only works for Poke Gal, will add Mewbot and Poketwo.

## Prerequisites
You need Windows 10 installed. This has not been tested with macOS or Linux.

You need to have Node.JS v13.x & NPM v6.x installed.

You should have a private Discord server ready to use

## Getting Started

1. Go to the Discord Developers Portal and create a new app. Go to the bot tab and tick 'Add Bot'
2. Get the invite link to your bot (under the oAuth2 tab) and invite it to your private server
3. Go back to the bot tab and copy the token.
4. Download and extract the latest release from this repository (v2).
5. Open `config/options.json`.

5.a Change the field `"foolToken"` to the token you copied earlier.

5.b [Optional] Change the field `"prefix"` to the prefix you would like to trigger THIS bot with.

5.c [Optional] Change the field `"userId"` to your Discord ID. To get this info, enable Developer Mode in appearance settings and right click your name.

5.c [Optional] Change the field `"interval"` to the interval you want the bot to spam at (in ms).

### We're almost ready to run the bot
6. Open the terminal in the folder that Fool is in.

6.a Run the command `npm i` and wait for all the dependencies to be installed.

6.b Run the command `node .` and the bot will start running.

7. Enjoy and catch em' all!
