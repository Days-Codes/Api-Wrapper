<div align="center">
  <h1>Day Api</h1>
  <p>
    <a href="https://www.npmjs.com/package/space-api-wrapper"><img src="https://img.shields.io/npm/v/popcat-wrapper?maxAge=3600" alt="NPM version" /></a>
    <a href="https://www.npmjs.com/package/space-api-wrapper"><img src="https://img.shields.io/npm/dt/popcat-wrapper?maxAge=3600" alt="NPM downloads" /></a>
  </p>
  <p>
    <a href="https://www.npmjs.com/package/space-api-wrapper"><img src="https://nodei.co/npm/space-api-wrapper.png?downloads=true&stars=true" alt="NPM Banner"></a>
  </p>
</div>

# Community
<p>Join <a href="https://discord.gg/Wee9zCbDXr">Our Server</a> If you want to have fun or need any support!</p>
 
## Installation

npm i 
## Examples

```js
const space = require("day-api")
const joke = await space.joke()
const Discord = require("discord.js")
const client = new Discord.Client()


client.on("message", async message => {
if (message.content.toLowerCase() === ">job") {
  const joke = await space.joke()
  message.channel.send(joke)
}
})

client.login("bot token")
```

## Endpoints
You can get a full list of the possible API endpoints [Here](https://api.popca.xyz)
But here is the list:
 - `joke()`
- `duck()`
- `meme()`
- `duck()`
## Credits
Made with ❤ by Zero Two#9999
Modified with 💖 by Dayln#0001

