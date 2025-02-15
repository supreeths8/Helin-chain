# React Truffle Box

This box comes with everything you need to start using Truffle to write, compile, test, and deploy smart contracts, and interact with them from a React app.

## Installation

First ensure you are in an empty directory.

Run the `unbox` command using 1 of 2 ways.

Only if you want to create a new dapp follow the next two commands else leave.
```sh
# Install Truffle globally and run `truffle unbox`
$ npm install -g truffle
```

Start the react dev server.

```sh
$ cd client
# Remove the package-lock.json file if it's already there
$ npm install
$ npm start
  Starting the development server...
```
If it does not work this way then first try these commands to build truffle.

Make sure truffle version is : Truffle v5.7.4 (core: 5.7.4).

```sh
$ cd truffle
$ truffle compile
$ truffe migrate
```

From there, follow the instructions on the hosted React app. It will walk you through using Truffle and Ganache to deploy the `SimpleStorage` contract, making calls to it, and sending transactions to change the contract's state.

## FAQ

- __How do I use this with Ganache (or any other network)?__

  The Truffle project is set to deploy to Ganache by default. If you'd like to change this, it's as easy as modifying the Truffle config file! Check out [our documentation on adding network configurations](https://trufflesuite.com/docs/truffle/reference/configuration/#networks). From there, you can run `truffle migrate` pointed to another network, restart the React dev server, and see the change take place.

- __Where can I find more resources?__

  This Box is a sweet combo of [Truffle](https://trufflesuite.com) and [Create React App](https://create-react-app.dev). Either one would be a great place to start!
