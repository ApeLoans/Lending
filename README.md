# Ape.Loans Lending Platform

Peer-2-Peer Lending Platform on ApeChain.


# About

In the traditional banking world, profits often come first. Higher interest rates burden borrowers, investors see poor returns, and hidden fees catch customers off guard. 

We said enough. Ape.Loans is a fair, transparent P2P lending platform on ApeChain, built for the NFT and crypto community. Borrowers and lenders connect directly, setting terms with clear fees. Our NFT holders gain utility through liquidated profits, distributed monthly. 

Powered by ApeCoin speed and security, we’re redefining lending, putting trust and transparency first.


# Features

  - Peer-to-Peer NFT Loans
  - Peer-to-Peer ApeChain Crypto Loans
  - Real-Time Oracle Data for Loans
  - Automatic Liquidation Options for Lenders
  - User-Friendly Dashboard
  - Security Measures
  - P2P Risk Management


### Further development

  - Improve external contract calls
  - Minimize gas cost
  - Create more investors protection
  - Automated Risk Scoring
  - Lending Pools
  - Enhanced NFT Utility


### Requirements
* [Node.js](https://nodejs.org/)
* [Truffle](https://truffleframework.com/)
* [Ganache](https://truffleframework.com/ganache/)
* [MetaMask](https://metamask.io/)
    

### Installation

1. Start Ganache on ``localhost:7545``   

2. Build and migrate smart contracts

```sh
$ cd p2p-lending/smart-contracts
$ truffle compile
$ truffle migrate --reset --network development --verbose-rpc
```

3. Set the ``PeerToPeerLending`` contract newly published address in the [client-app/public/js/contract_interaction.js 

4. Install the dependencies and devDependencies and start the server.

```sh
$ cd p2p-lending/client-app
$ npm install --save
$ npm start
```

5. Your app is running on ``http://localhost:1337``

# Author

        Smokish 
        Email - loansonape@gmail.com

# Acknowledgments

    smokethatdank.eth - https://x.com/smokethatdank1
    Apes on Ape - http://www.apesonape.io

# License

  MIT
