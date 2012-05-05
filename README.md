#Getting Started
The following will be needed before beginning:
 - A modern web browser supporting HTML5
 - [Node.js](https://github.com/joyent/node) v0.6.x

###Changing Node.js version
The package.json file is set node version 0.6.15 but you should be able to change that to any 0.6.x. If your node version is different and you are looking for an easy way to switch versions just run:

	npm intall n -g

To switch to 0.6.15 just type:
	
	n 0.6.15
	
And your node version will be changed to 0.6.15.

##Let's begin
Start by cloning the repo:

	mkdir fi
	cd fi
	git clone git@github.com:chrisabrams/Fi.git
	
Now install the needed NPM modules for node:

	npm install
	
###Start the Server

	npm start
	
Try accessing the server at [http://localhost:8081](http://localhost:8081) and give it a go.