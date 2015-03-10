#**How to get your AngularJS and Web Developper Environment Ready With Web Development with AngularJS, NodeJS, ExpressJS and Yeoman(Yo, Grunt and Bower)?**

##1. Install JetBrains WebStorm 9.0.3 

Install JetBrains WebStorm 9.0.3 by downloading it from https://www.jetbrains.com/webstorm/.

##2. Install NodeJS 

Go to https://nodejs.org/ and install the application. Note that NodeJS does not have a GUI therefore you will have to setup your Environment Variable to be able to call it anytime at the terminal (Windows Environment). Check your Node.js version by running the following command at the terminal. npm –version

##3. Install ExpressJS 

Install ExpressJS module of node.js (Web Server) by running the following command at the terminal: npm install –g express-generator. Test you system to see if everything is OK by doing the following:
- 1.	Create a folder call myapp
- 2.	Type the following command at the terminal. express myapp 
- 3.	cd myapp and check if you have a bunch of file in the folder
- 4.	Run the following command at the terminal npm install
- 5.	Finally in the terminal type in the following command: npm start
- 6.	Open your browser and type http://localhost:3000 in the address bar to view the ExpressJS Welcome webpage. If everything goes well you are doing great.

##4. Install Grunt 

Installing Grunt (A javaScript-based task runner). It is used for automating task like unit test, concatenating, merging and minifying JS and CSS file. To install Grunt do the following: npm install –g grunt-cli at the terminal.

##5. Install Yeoman 

Installing Yeoman(It is a collection of tools that allows you to manage your workflow). 
- Yo is a scaffolding tool and using the numerous generators available, one can quickly create the skeleton of your project. To install Yo run the following command: npm install –g yo
- Grunt is used to run the tasks that will help you preview, test, and build the app. 
- Bower is an ideal tool for dependency management. Yeoman uses it to automatically search and download the necessary scripts. To install bower run the following command: npm install –g bower


##4. References

A great training reference for starter is the book: Practicing AngularJS in HTML: Volumes 1 & 2 by Tony de Arau Jo.
Another great reference for developper is: AngularJS Web Application Development Blueprints by Vinci Rufus.

