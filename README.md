<p align="center">
	<img height="200" width="500" src="https://i.imgur.com/owrQCO9.png">
	<p align="center"><a href="https://www.npmjs.com/~cerusjs">NPM</a> | <a href="https://github.com/cerusjs">Github</a> | <a href="https://cerusjs.github.io/">Docs</a></p>
</p>

Welcome to the home page for CerusJS! CerusJS is a modular, and even more important, understandable NodeJS framework. The whole framework is designed to be easy to learn and use. Since all names are styled the same and a similar styling is used all across the framework all plugins and their modules will be intuitive to use.
Since CerusJS is also modular, loading times can be decreased drastically since you only use and load the parts you need. This modularity will also improve the usability among other things. Having said that, everything is still open source and available under a [single user](https://github.com/cerusjs). This information "module" contains all the basic tutorials you need when starting out with CerusJS. For more detailed tutorials and the full reference per module you can just click on that module.


## Installation
Installing CerusJS is pretty easy since it is available through [NPM](https://www.npmjs.com/), but before reading further please make sure you have NodeJS (which also installs NPM by default). When starting out it is recommended to start with the cerus module. It contains all the basic modules you'll need to create a server and other things. From that point installing and using other modules it will be as easy as ABC. Use the following command to install the cerus module:
```bash
# Installs the latest version of CerusJS.
$ npm install cerus
```


## A short example
The following example shows how the create and start a server:
```javascript
var cerus = require("cerus")();
cerus.server().start();
```


## Modules
This is a list of all the official modules. Some modules can be an abstract layer, so they will need a driver to be used with it. Read more about this [here](#).
- [cerus](/views/cerus/readme.html): This is the main module, meaning it contains all the starter modules needed to create things like a basic server. It also contains some utils for easily routing files and for requiring files.
- [cerus-core](/views/cerus-core/readme.html): This is the core for CerusJS. It has only one function: to add other modules to the cerus instance. This basically means this module will stand in the middle of it all.
- [cerus-server](/views/cerus-server/readme.html): With the cerus-server module you can create basic HTTP servers. It also contains server-related functions to help you. Warning: this will be replaced by another module in the future, meaning it won't be supported anymore.
- [cerus-router](/views/cerus-router/readme.html): This is the router module, with it you can route incoming HTTP requests based on the requested URL. It will also build the request and response class that come with the request.
- [cerus-api](/views/cerus-api/readme.html): With the cerus-api module you can route RESTful (JSON) requests. It contains a custom response class that will be used to append the JSON response to.
- [cerus-promise](/views/cerus-promise/readme.html): This is the custom promise for CerusJS. It is build from scratch to not only support the basic promise methods, but to also include easy stacking and custom events.
- [cerus-fs](/views/cerus-fs/readme.html): With the cerus-fs module you can easily interact with your file system. It is split in to groups: files and folders, which make it easier to use and they each contain their own functions.
- [cerus-compression](/views/cerus-compression/readme.html): This module is used to easy the compression process. You can automatically compress data with it or just create a stream to compress at will.
- [cerus-uuid](/views/cerus-uuid/readme.html): The cerus-uuid module is used to work with UUIDs. With it you can generate truly unique UUIDs.
- [cerus-ejs](/views/cerus-ejs/readme.html): This is the EJS module for CerusJS. It is used to parse EJS files and even has a custom including system.
- [cerus-sessions](/views/cerus-sessions/readme.html): With this module a router can create it's own sessions. These sessions can be used to store client information in a safe way.
- [cerus-database](/views/cerus-database/readme.html): This is the database layer for CerusJS. With it you can easily interact with all the supported database types, like Mongo, MySQL, etc.
- [cerus-hash](/views/cerus-hash/readme.html): With the cerus-hash module you can encrypt/decrypt data, hash data and it even includes helpers for peer to peer encryption.
- [cerus-request](/views/cerus-request/readme.html): The cerus-request module is a custom request module you can use to check if your server is behaving correctly.


## Contributers
The author of CerusJS is [JortvD](https://github.com/JortvD).