Fire.io
=============

[![GitHub Stars](https://img.shields.io/github/stars/huytd/agar.io-clone.svg)](https://github.com/huytd/agar.io-clone/stargazers)
[![GitHub Issues](https://img.shields.io/github/issues/huytd/agar.io-clone.svg)](https://github.com/huytd/agar.io-clone/issues)
[![GitHub Wiki](https://img.shields.io/badge/project-wiki-ff69b4.svg)](https://github.com/huytd/agar.io-clone/wiki/Home)
![Build Status](https://api.travis-ci.org/huytd/agar.io-clone.svg)
[![Live Demo](https://img.shields.io/badge/demo-online-green.svg)](#live-demo) "
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/huytd/agar.io-clone?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A simple Agar.io clone built with socket.io and HTML5 Canvas on top of NodeJS.

![Image](http://i.imgur.com/O3rP7cg.png)

## Live Demos
An updated list of live demos can be found on the [Live Demos wiki page](https://github.com/huytd/agar.io-clone/wiki/Live-Demos)

---

## How to Play
>You can check out a more elaborated how to play on our [wiki](https://github.com/huytd/agar.io-clone/wiki/How-to-Play)

#### Game Basics
- Move your mouse on the screen to move your character
- Eat food and other players in order to grow your character (food respawns every time a player eats it)
- A player's **mass** is the number of food particles eaten
- **Objective**: Try to get fat and eat other players

#### Gameplay Rules
- Players who haven't eaten yet cannot be eaten
- Everytime a player joins the game, **3** food particles will spawn
- Everytime a food particle is eaten by a player, **1** new food particle will respawn
- The more food you eat, the slower you move

---

## Latest Changes
- Game logic handled by server
- Client side is for rendering only
- Display player name
- Now supporting chat 
- Type`-ping` in the chatbox to check your ping

---

## Installation
You can simply click one of the buttons below to easily deploy this repo to Bluemix or Heroku:

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/huytd/agar.io-clone)
[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## License
>You can check out the full license [here](https://github.com/huytd/agar.io-clone/blob/master/LICENSE)

This project is licensed under the terms of the **MIT** license.
