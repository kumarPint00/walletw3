# TOT Wallet
This project is a decentralized cryptocurrency wallet application that enables users to securely store, send, and receive cryptocurrencies.

# Project Structure
## Client
This directory contains the frontend code for the cryptocurrency wallet.

* Images:
  * animated.svg: An animated SVG graphic.
  * hello.svg: A static SVG graphic.
  * logo.png: The application's logo.
* Source Code:
  * .eslintrc.js: ESLint configuration file.
  * .gitignore: Git ignore file specifying untracked files.
  * .prettierrc: Prettier configuration file.
  * index.html: Main HTML file for the client-side application.
  * package-lock.json: Dependency lock file for npm.
  * package.json: Project metadata and dependencies.
  * postcss.config.js: PostCSS configuration file.
  * tailwind.config.js: Tailwind CSS configuration file.
  * vite.config.js: Vite configuration file.
  * yarn.lock: Dependency lock file for Yarn.
  
## Smart Contract
This directory contains the smart contract code and related scripts for the cryptocurrency wallet.

* Contracts:
  * Transactions.sol: Solidity smart contract for handling transactions.
* Scripts:
  * deploy.js: Script to deploy the smart contract.
* Tests:
  * sample-test.js: Sample test script for the smart contract.

# Getting Started
## Prerequisites
* Node.js and npm (or Yarn)
* A web browser (for the client-side application)

## Installation
1. Clone the repository:
   `git clone https://github.com/ggwpfax/crypto-wallet.git`
   `cd crypto-wallet`
2. Install client dependencies:
  `npm install` or `yarn install`

## Usage
1. Run the client-side application:
  `npm run dev` or `yarn dev`