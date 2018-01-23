##Node Concepts

Building Blocks
* Libuv: to support node js in windows Enviorment
* v8 Engine: 
* js/c++:

#NPM vs NVM (Not supoorted by windows)

NPM  is node package manager Where as NVM is node version manager.
nvm (Node version manager) is a command line interface (CLI) to install different versions of nodejs in your machine. 
Whereas npm (node package manager) is a CLI for managing your node modules (e.g. Creating a package, etc).


nvm (Node Version Manager) is a tool that allows you to download and install Node.js. 
* Check if you have it installed via nvm --version.
else
* curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.26.1/install.sh | bash

npm (Node Package Manager) is a tool that allows you to install javascript packages.
npm comes with Node.js so if you have node installed (node --version) you have npm installed as well.
You don't need nvm unless you you want to keep multiple versions of Node.js installed on your system or if you'd like to upgrade your version.

#Node Event loop 

* Each events that are being fire is deiscrete.
* Node doesn't pause and wait for event.
    For Example:

    Http request sent ---> Request Recevied by Node server ---> node forwarded that event to db and now free to get other reuest.
