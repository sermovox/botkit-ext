# [Botkit](https://botkit.ai) - Building Blocks for Building Bots



[![npm](https://img.shields.io/npm/v/botkit.svg)](https://www.npmjs.com/package/botkit)
[![David](https://img.shields.io/david/howdyai/botkit.svg)](https://david-dm.org/howdyai/botkit)
[![npm](https://img.shields.io/npm/l/botkit.svg)](https://spdx.org/licenses/MIT)
[![Build Status](https://travis-ci.com/howdyai/botkit.svg?branch=master)](https://travis-ci.com/howdyai/botkit)

** the fork contains some reference to work with a voice fw 

**Botkit is the leading developer tool for building chat bots, apps and custom integrations for major messaging platforms.**


## Install Botkit

Botkit is a Node.js module, and works with Node and npm.



### **Command Line Interface**

The best way to get started locally with Botkit is by installing our command line tool, and using it to create a new Botkit project. This will install and configure a starter kit for you!

```
npm install -g botkit
botkit new
```

### **Start from Scratch**

You can also add Botkit into an existing Node application.

First, add it to your project:

```
npm install --save botkit
```

Then, add Botkit to your application code:

```
var Botkit = require('botkit');

var controller = Botkit.anywhere(configuration);

controller.hears('hello','direct_message', function(bot, message) {
    bot.reply(message,'Hello yourself!');
});

## About Botkit

Botkit is a product of [Howdy.ai](https://howdy.ai).


Botkit is released under the [MIT Open Source license](LICENSE.md)
