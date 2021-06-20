# EZ Modmail

![](https://img.shields.io/badge/Discord%20Bot-discord.js-9cf)

EZ Modmail is an open-source Discord modmail bot designed for individual servers, with a quick and easy setup process that should get your new modmail bot running in no time!


![mmChat](https://cdn.discordapp.com/attachments/764224430649376769/773321003916460082/unknown.png)
###### Above: Closed Pre-Release version, some colors have been changed for the final release.
## Installation

### Requirements
- Node.JS installed 

- Discord.JS library installed

- A Discord Bot Application*

- A main server, and a modmail server with a logging category and channel, and a tickets/modmail category (and their respective IDs)

- A text editor capable of editing JSON files (default windows notepad works just fine)

###### *The bot must have PRESENCE INTENT and SERVER MEMBERS INTENT enabled, or else the script will error. It should also be given administrator permissions in the OATH2 category (BOT\BOT PERMISSIONS)
Getting Token:
![exampleImage0](https://cdn.discordapp.com/attachments/764224430649376769/773306714418053190/unknown.png)
Setting Privileged Gateway Intents:
![exampleImage1](https://cdn.discordapp.com/attachments/764224430649376769/773305848969560094/unknown.png)
### Setup
1. Download the files (if you are hosting on a VPS or some other type of server, upload them to that)

2. Replace the following with your specific bot/server info in config.json
```json
{
    "token":"YOUR BOT TOKEN HERE",

    "ticketCategoryID":"THE ID OF THE CATEGORY FOR TICKETS TO BE OPENED (MUST BE IN MODMAIL SERVER!)",

    "modmailServerId":"ID OF THE MODMAIL SERVER",

    "thumb":"LINK TO THE IMAGE TO BE USED FOR MODMAIL EMBEDS",

    "modmailLogChannelId":"ID OF THE LOGGING CHANNEL",

    "mainServerId":"ID OF THE MAIN SERVER"



}
```
3. Once you have entered all the information above, run the modmail.js file.

## Usage

### Commands:
[PREFIX IS `!mm `]

`reply` : ``Reply to a ticket``

`areply` : ``Reply to a ticket anonymously ``

`close` : ``Close the ticket that you are currently responding to``

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. 


If there are any major issues that you need fixed ASAP, join the support server:

 [WIP, will be added soon!] 


(friend request baguette#6969 (Nitro) or baguette#1538 (Normal) until server is added)


## License
[GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.en.html)
