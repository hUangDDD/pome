## pome(pomelo) -- a fast, scalable game server framework for node.js

pome is a fast, scalable game server framework for [node.js](http://nodejs.org).
It provides the basic development framework and many related components, including libraries and tools.
pome is also suitable for real-time web applications; its distributed architecture makes pome scale better than other real-time web frameworks.

[![Build Status](https://travis-ci.org/NetEase/pome.svg?branch=master)](https://travis-ci.org/NetEase/pome)

 * Homepage: <http://pome.netease.com/>
 * Mailing list: <https://groups.google.com/group/pome>
 * Documentation: <http://github.com/NetEase/pome>
 * Wiki: <https://github.com/NetEase/pome/wiki/>
 * Issues: <https://github.com/NetEase/pome/issues/>
 * Tags: game, nodejs


## Features

### Complete support of game server and realtime application server architecture

* Multiple-player game: mobile, social, web, MMO rpg(middle size)
* Realtime application: chat,  message push, etc.

### Fast, scalable

* Distributed (multi-process) architecture, can be easily scale up
* Flexible server extension
* Full performance optimization and test

### Easy

* Simple API: request, response, broadcast, etc.
* Lightweight: high development efficiency based on node.js
* Convention over configuration: almost zero config

### Powerful

* Many clients support, including javascript, flash, android, iOS, cocos2d-x, C
* Many libraries and tools, including command line tool, admin tool, performance test tool, AI, path finding etc.
* Good reference materials: full docs, many examples and [an open-source MMO RPG demo](https://github.com/NetEase/pome/wiki/Introduction-to--Lord-of-pome)

### Extensible

* Support plugin architecture, easy to add new features through plugins. We also provide many plugins like online status, master high availability.
* Custom features, users can define their own network protocol, custom components very easy.

## Why should I use pome?
Fast, scalable, real-time game server development is not an easy job, and a good container or framework can reduce its complexity.
Unfortunately, unlike web, finding a game server framework solution is difficult, especially an open source solution. pome fills this gap, providing a full solution for building game server frameworks.
pome has the following advantages:
* The architecture is scalable. It uses a multi-process, single thread runtime architecture, which has been proven in the industry and is especially suited to the node.js thread model.
* Easy to use, the development model is quite similar to web, using convention over configuration, with almost zero config. The [API](http://pome.netease.com/api.html) is also easy to use.
* The framework is extensible. Based on the node.js micro module principle, the core of pome is small. All of the components, libraries and tools are individual npm modules, and anyone can create their own module to extend the framework.
* The reference materials and documentation are quite complete. In addition to the documentation, we also provide [an open-source MMO RPG demo](https://github.com/NetEase/pome/wiki/Introduction-to--Lord-of-pome) (HTML5 client), which is a far better reference material than any book.

## How can I develop with pome?
With the following references, you can quickly familiarize yourself with the pome development process:
* [pome documents](https://github.com/NetEase/pome/wiki)
* [Getting started](https://github.com/NetEase/pome/wiki/Welcome-to-pome)
* [Tutorial](https://github.com/NetEase/pome/wiki/Preface)


## Contributors
* NetEase, Inc. (@NetEase)
* Peter Johnson(@missinglink)
* Aaron Yoshitake 
* @D-Deo 
* Eduard Gotwig
* Eric Muyser(@stokegames)
* @GeforceLee
* Harold Jiang(@jzsues)
* @ETiV
* [kaisatec](https://github.com/kaisatec)
* [roytan883](https://github.com/roytan883)
* [wuxian](https://github.com/wuxian)
* [zxc122333](https://github.com/zxc122333)
* [newebug](https://github.com/newebug)
* [jiangzhuo](https://github.com/jiangzhuo)
* [youxiachai](https://github.com/youxiachai)
* [qiankanglai](https://github.com/qiankanglai)
* [xieren58](https://github.com/xieren58)
* [prim](https://github.com/prim)
* [Akaleth](https://github.com/Akaleth)
* [pipi32167](https://github.com/pipi32167)
* [ljhsai](https://github.com/ljhsai)
* [zhanghaojie](https://github.com/zhanghaojie)
* [airandfingers](https://github.com/airandfingers)

## License

(The MIT License)

