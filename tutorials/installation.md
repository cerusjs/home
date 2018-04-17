# Installation
This tutorial will explain how you can install CerusJS. Currently it's pretty easy, but it'll probably change in the future making it easier and more scalable. But you don't have to worry, the original installation process is still going to work. Having said that, the current installation system requires nothing more than NPM.

## Dependencies
To install CerusJS you need NPM and to run the projects you are going to create you need NodeJS. If you've already installed both of these you can go ahead to the next paragraph. When installing NodeJS it will automatically also download NPM. The download for NodeJS/NPM is available on [this](https://nodejs.org/en/download/) link. Choose the installer for your operating system. Go through the installation process and when the installation has completed you can test it with the following command.
```bash
# Returns the install version of NodeJS
$ node -v
```
If NodeJS is installed correctly it should return a version number. Since NodeJS is now installed NPM should also be there and you can now head on to the next paragraph.

## Installing the basic module
When you're starting out it is recommended to install the cerus module. This module can be found as "cerus" on NPM and contains the basic modules you'll need to create things like servers. For more information about this module you can look at it's readme [here](/views/home/readme.html). To install this module and the other modules you will need NPM, so check to paragraph above if you haven't already. You'll need to install the module in your project folder. This is the folder where you want to work on your project and from where you want to run your project. Please empty the folder before using the command to avoid overwriting problems.
```bash
# Installs the latests version of the cerus module.
$ npm install cerus
```
After you call this command there should be a new file and folder in your project folder. The "package.json" file that was created contains the configuration for NPM. The "node_modules" folder contains the modules that were installed by NPM. You learn to add other modules in the next paragraph. These new modules will also be installed into the "node_modules" folder.

## Installing a specific module
There is basically no difference between this installation process and installing the basic module. Just like before you'll need NPM. Please note that [MODULE] is the name of the module you want to install. Most cerus modules will start with the "cerus-" prefix, so check you have added that before installing the module. This command also needs to be run inside your project folder.
```bash
# Installs the specified module.
$ npm install [MODULE]
```
