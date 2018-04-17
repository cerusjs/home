# Your first application
This tutotial will help you creating your first application. An application is a program that executes a bunch of actions. Before you can start writing code you need to choose a project folder. Read the previous tutorials if you haven't yet installed NodeJS and the basic cerus module. Now everything is installed and ready, you can create a new file with a name of your choosing. Keep in mind the extension of the file needs to be ".js" for it to be recognized as a javascript file. If this is new to you it is suggested to learn some javascript before continuing with these tutorials. Now you can add the following line of code to your file:
```javascript
var cerus = require("cerus")();
```
In this single line of code a variable is created with as value an initialization of the required module. This means that the specified module is loaded using NodeJS' require function and after that the loaded class is initialized. During this initialization the value that will be returned is created. This line won't produce everything noticable, but that will come in the next tutorials.