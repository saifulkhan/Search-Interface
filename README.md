
# About 
This is a research prototype of (a) an Enterprise Search Engine (C++) and (b) a Search Interface (Qt and Angular, d3). 

This repository contains the  Search Interface (front-end code).
Entire version of the prototype (part of my DPhil) is not open sourced. This code contains minimal comments and test cases.
The [Enterprise Search Engine](https://github.com/saifulkhan/Enterprise-Search-Engine) can be found in an another repository. 

Search interface support two mazor functionalities (a) search result and search space visualization for rapid interpretation of search results and (b) search collaboration. 

 
# Prerequisites : Web-tools

node version: v0.10.33
npm version: 1.4.28

- `$ wget  https://nodejs.org/dist/v0.10.33/node-v0.10.33-linux-x64.tar.gz`
- `$ tar -xvf node-v0.10.33-linux-x64.tar.gz`
- `$ sudo cp -rf node-v0.10.33-linux-x64/* /usr/local/`


# Dependencies : Search Engine Back-end 


# Run

To install this project in your local machine and begin developping, you need to follow these steps:

- `sudo npm install`
- `bower install`
- `grunt serve` <-- run this project in development mode 


## Testing

- `grunt test`  <-- will run the client and server unit tests with karma and mocha.
- `grunt test:server` <-- to only run server tests.
- `grunt test:client` <-- to only run client tests.
 

 
