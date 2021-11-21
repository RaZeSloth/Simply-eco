<h2 style="font-size:6.5rem; color:#F4B3CA" align="center"> Simply Eco </h2>
<p align="center"><img align="center" style="width:0.5px" src="https://i.imgur.com/DWeejI6.jpg"/></p><br/>
<p align="center">
  <a href="https://www.npmjs.com/package/simply-eco"><img src="https://img.shields.io/npm/v/simply-eco.svg?style=flat-square" /></a>
 <a href="https://www.npmjs.com/package/simply-eco"><img src="https://img.shields.io/npm/dt/simply-eco?style=flat-square" /></a><br>
   <a href="https://www.npmjs.com/package/simply-eco"><img src="https://nodei.co/npm/simply-eco.png?downloadRank=true&downloads=true&downloadRank=true&stars=true" /></a><br>
  <a href="https://discord.gg/HNfhvCeR6d"><img src="https://invidget.switchblade.xyz/HNfhvCeR6d" alt="Discord"></a>
</p>


> **Simply Eco is a powerful module that allows you to create economy system in your bot with ease.:)**

## **Installation** 

```js
npm install simply-eco
```

## Without Customization 

```js
//Import package
const economy = require("simply-eco");
//create new economy() Class
const eco = new economy.eco("YOUR MONGODB URI")

eco.<Method>(<Options>); //return -> Promise ->
```


## With Customization 

```js
const eco = new economy.eco('YOUR MONGODB URI', {
notify: false
});

// use the methods
eco.<Method>(<Options>); //returns -> Promise -> 
```

# Options

- **📌 notify** `(Boolean)` - Notifies when SimplyEco is connected

## Features

- Super simple
- Easy to use
- Works with Discord.js v12 and v13
- Works with both Slash and Prefix Commands 
- Great Support
- Fully Customizable

## LINKS

- 📃 Example Bot: [Link](https://github.com/Xx-Mohit-xX/Simply-eco/tree/main/Example-Bot)
- 📃 Discord: [Server](https://discord.com/invite/HNfhvCeR6d)


## Credits

- Modified by: [@Xx-Mohit-xX](https://github.com/Xx-Mohit-xX)
- Made by: [@Yash094](https://github.com/Yash094)