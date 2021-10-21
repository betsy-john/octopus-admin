# octopus-admin
This is Octopus React UI

This is a react UI front.
This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Before you begin!

Before you begin you might want to read how reactjs framework works.
The other libraries used in the project are

[Axios](https://socket.io/docs/) -> Invoke external API.

[React Router](https://reactrouter.com/) -> To manage the routing of the application.

[react-bootstrap](https://react-bootstrap.github.io/) -> To render UI with bootstrap CSS framework

[react-hook-form](https://react-hook-form.com/) -> To work with HTML Forms.

## Prerequisites

To run the application on your local machine, make sure you have installed all of the following prerequisites on your development machine:

Git - Download & Install Git. OSX and Linux machines typically have this already installed.

Nodenv - Download & Install Nodenv (https://github.com/nodenv/nodenv) with node-build plugin

After you install git and nvm you can then install node - Project requires node version 12.16.0 or above.

```bash
$ nodenv install 12.18.0
$ nodenv local 12.18.0
```

Next update to the latest version of npm (Node Package Manager).

```bash
$ npm i -g npm
```

## Get the source

Find (or create) the folder in which you will downloading the source code. In my case I use ~/projects/idyllwild/

```bash
$ mkdir ~/projects/idyllwild/idyllwild-admin
$ cd ~/projects/idyllwild/idyllwild-admin
```

Then clone the repository

```bash
$ git clone git@github.com:v2dev/idyllwild-admin.git .
```
change the directory to octopus-admin
Next install all of the npm (package.json)

```bash
$ npm install
```

## Start the application

```bash
$ npm start
```
