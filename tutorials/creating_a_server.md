# Creating a server
If you haven't seen the previous tutorials, please do. They contain some important information you'll need for this tutorial. So, we now know how to create the cerus variable containing the initialized cerus class. The next step is to create your first server. To do this we will use the following code:
```javascript
var cerus = require("cerus")();

cerus.server().start(function() {
	console.log("the server has started");
});
```
This code will first create the cerus class, as explained in the previous tutorial. In the lines after that it will call the server function assigned to the cerus class. This function will return the server class. This class was initialized when cerus was loaded, meaning you don't have to initialize it yourself. Then the start function is called which starts the server. The callback that is passed on in the function will be called after the server has been started. When that happens the server will log "the server has started". If there is an error, first try to reinstall cerus and if that doesn't work you can open an issue on the cerus repository on github containing the error. You can stop the program with CTRL + C on Windows, Linux and Mac.