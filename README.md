# CriminalRecord

## Bot Aims

CriminalRecord is a discord bot focusing on informing admins and server owners of rulebreakers before they cause issues. It is designed to help inform decisions on punishments; in a situation where you're not sure whether a member's behaviour classes as advertising, look at their global history. If they've been caught advertising before on any server, you will know.

## Getting Started

### Inviting

To invite to your server just use the [invite link](https://google.com)

### Config

Create a channel for the bot in your server. Ensure that your staff can read this and send to it but normal members cannot. Then type in the channel `cr.setchannel main`. The bot will remember the logging channel. When any member joins they will automatically be checked against in the database and if any previous punishments show up, the channel will be alerted

## Usage

### Giving out punishments

To punish a player first ensure their punishment complies with one of the globally punishable offences. If not, but you still wish to punish them, use discord's built in punishment features. Once you have determined which offence they have commited, run the following command:
```
cr.punish <username#1234> <punishment id> <consequence id> | [Evidence]
```
As you can see, you can choose the consequence according to your server's preferences. Providing evidence is important as if the ban is appealed this is needed (see the appealing section)

## Transparency

When a player is punished they are direct messaged information about their punishment. 
They can choose to appeal if they wish, however a successful appeal **does not mean the punishment has to be revoked**, if the appeal is successful the log will only be deleted from the database

## Built With
* Discord.JS

## Authors / Contributors

* **Jay Williams** - *Bot designer* - [codingJWilliams](https://github.com/codingJWilliams)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

