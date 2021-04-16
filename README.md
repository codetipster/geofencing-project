# INTRO
Welcome to the Project! Our aim here was to build a geofencing mobile app with IoT efficiency. The project was part of our first core semester project at CODE.

## Requirements
- React-native documentation https://reactnative.dev/docs/environment-setup
- Android Visual Studios
- Node.Js
- Watchman(Optional, but highly recommended)

## Set-Up(Environment):
Open terminal(Ctrl+shift+t) and check to see if you have node installed( $ node --version). As at the time of writing this, the latest version of node was V15.14.0, if yours is a lower version, you can update your version as follows:

## Update Node.Js
There are different ways to update Node.js if you are using a Linux-based system. Although using the Node Version Manager is the easiest and most recommended option, you can also update with the local package manager or by downloading the binary packages.

The best way to upgrade Node.js is with NVM, a practical tool for managing multiple Node.js versions.

Begin by updating your package repository: $ sudo apt update

Download dependencies: $ sudo apt install build-essential checkinstall libssl-dev

Install NVM using curl: curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.35.1/install.sh | bash

NB: You can install curl with the terminal instruction and then re-run the last command line above.

Now, close and reopen your terminal and test to see that NVM is installed with $ nvm --version

Check the versions of NODE available with $ nvm ls

Run: $ nvm ls-remote

To install the latest version, use the nvm command with the specific Node.js version:
$ nvm install [version.number]