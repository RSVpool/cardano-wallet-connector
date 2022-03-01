# Modified for submitting custom transactions through wallet connector

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### React JS demo

In the project directory, you can run: `npm start run`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.


This boilerplate code was written in javascript and React Js, so caters to the devs who already use this framework. Thee boilerplate should allow anyone to read it and

### How does it work:
- It uses the wallet connector standard CIP30 and the cardano-serialization-lib
- the CIP30 standard has been implemented by Nami, CCvault and Flint
- It uses the cardano-serializatioon-lib to build transactions in the javascript front-end, then sign them and send the transactrons with the user's wallet
- you can clone the git repo and then `npm instal`l and `npm start run` to start a local session

### What does it do:
- resign and send cardano-cli transaction through dapp connector


