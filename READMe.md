# Mevn-Cli
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

A CLI tool for getting started with MEVN stack. It offers a [super simple boilerplate project](https://github.com/Madlabsinc/mevn-boilerplate) and additional utilities for building a MEVN app. It helps developers who are beginners, to easily create a template for their Web application development.

## Getting Started

 Currently, this tool only works on Linux.


### Prerequisites

- Npm - it is a package manager for the JavaScript programming language.
- Node.js -Node.js is an open-source, cross-platform JavaScript run-time environment that executes JavaScript code outside of a browser.
- Git - Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for source code management in software development.

### Installing

To install the package :-
```
npm install -g mevn-cli
```

## Commands




### Initial Command

This command Initialises the project.

```
mevn-cli init appname
```

### Server Commands

These commands are used to generate code necessary for running a server.

| command | description |
| ------- | ----------- |
|``` mevn-cli routes ``` | To create the Routes-File(API) |
|``` mevn-cli models ``` | To create the Models-File(SCHEMA) |
|``` mevn-cli controllers``` |  To create the Controllers-File |
| ```mevn-cli config ``` | To create the Config-File |


### General Command
 
 These are  commands to run the Client and Server

| command | description |																								
| -------------- |  ---------------- |
| ```mevn-cli server``` | To run the Server |
| ```mevn-cli client``` | To run the Client |


## Feautures

- This tool provides an easy way to build web app by providing a super simple boilerplate project to build up on.  
- Its written in ES6 syntax, which is an developer friendly syntax that keeps code simpler and smaller.
- The whole project is done in modules which enhances user readability and much more compact code.  
- Mevn-Cli will automate the files and generate the codes necessary to start and run a server,API etc


## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning And Help

| command | description
| --- | --- |
| ```mevn-cli -v``` | Check CLI version |
|``` mevn-cli --help ``` | Get help and check usage |

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Inspiration
