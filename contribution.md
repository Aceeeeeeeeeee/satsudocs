# Contributing

## How can I contribute?

1. You can send me (Arane#2756) snippets of code for commands or handlers etc.
2. You can request access to the project (which is on glitch as of right now)

## Command Handler Structure 

```js
module.exports = {
  name: "Your Command",
  description: 'Command Description',
  usage: "Command Usage",
  access: "Who can access the command",
  aliases: ["alias 1", "alias 2", "leave empty if none",]
  run: async(client, msg, args) => {
    //Below is your actual command code.
    msg.channel.send("Your command message")
    // More code here
  }
}
```

## Function Handler Structure

```js
module.exports = (client) => {
  client.functionname = (input) => {
    return //function code here
  }
}
```

## TL; DR

You can make what you want and send it to Arane#2756 on discord (If you are making a command, check above for the command handler structure). 

The other option is to DM Arane#2756 and ask if you can get access to the project. 
We currently work on [DanBot Hosting](https://panel.danbot.host), so you will need an account. 
All contributors should be proficcient in JavaScript(NodeJS) and have experience with using **discord.js v12** (discord.js v11 is deprecated, and there are a number of differences between v11 and v 12).

If you don't know NodeJS/discord.js at all but you would like to learn it, I suggest following the tutorial through these links.

[Discord JS Guide](https://discordjs.guide/) <br>
[Regular JavaScript (ES6) Guide](https://javascript.info/) <br>
[NodeJS and JavaScript Guide](https://nodeschool.io/) <br>

### Notes:
Discord.js is ran on NodeJS, and so you might also want to learn some npm basics to understand installing and uninstalling packages.
NodeJS is a backend language of Javascript, so you should learn Javascript *then* NodeJS specific features.