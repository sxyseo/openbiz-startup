Openbiz Startup
===============

What is it?
--------------------
The demo for how to start up with Openbiz framework. 
You can use it as a blank project template, and starts to build your own application based on it.
it is not a npm package, it an express based application

How to use it?
----------------------
You can clone the project and start to build and test your own module on it .

How to install (deploy)
-------------------------
```sh
#clone this project as your project's root folder
git clone https://github.com/openbiz/openbiz-startup.git

#go into the project folder
cd openbiz-startup

#clone openbiz server side framework into your project
git submodule add https://github.com/openbiz/openbiz.git  node_modules/openbiz 

#clone openbiz client side framework into your project
git submodule add https://github.com/openbiz/openbiz-ui.git  node_modules/openbiz-ui 

#clone openbiz client side application platform into your project
git submodule add https://github.com/openbiz/openbiz-cubi.git  node_modules/openbiz-cubi


npm install 

node app
```