# Project

[Reach Rock, Paper, Scissors! Tutorial](https://docs.reach.sh/tut/rps/)

## Stack

**Smart Contract**: [Reach](https://reach.sh/), Docker

**Frontend**: ReactJS, Javascript

**Wallet**: [MyAlgo Wallet](https://wallet.myalgo.com/home)

## Quick start

1. Install Reach with Docker [https://docs.reach.sh/quickstart/](https://docs.reach.sh/quickstart/)
2. Clone this repository [https://github.com/Biosmatrix/reach-rps.git](https://github.com/Biosmatrix/reach-rps.git)
3. `cd /reach-rps` change directory into the project folder on local machine
4. From the project root run `./reach compile` to compile the project in your Terminal
5. To run the dApp with Algorand call `REACH_CONNECTOR_MODE=ALGO ./reach react`
   - Your dApp should be running on [http://localhost:3000](http://localhost:3000)
   - Connect to the dApp with [MyAlgo Wallet](https://wallet.myalgo.com/home)
   - Get some algorand testnet faucet [Algorand Testnet Dispenser](https://testnet.algoexplorer.io/dispenser)

## Available Commands

- Compile the smart contract : Run `./reach compile` in your Terminal
- Run the smart contract : Run `./reach run` in your Terminal
- Run the dApp in development mode : Run `REACH_CONNECTOR_MODE=ALGO ./reach react` in your Terminal
