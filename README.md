# Ape.Loans Lending Platform
Peer 2 peer lending platform on ApeChain.

# About

In the traditional banking world, profits often come first. Higher interest rates burden borrowers, investors see poor returns, and hidden fees catch customers off guard.
 
Ape.Loans is a fair, transparent P2P lending platform on ApeChain, built for the NFT and crypto community. Borrowers and lenders connect directly, setting terms with clear fees. Our NFT holders (5,000+ collection) gain utility through liquidated profits, distributed monthly. 

Powered by ApeChain’s speed and security, we’re redefining lending, putting trust and transparency first.



# Features

  - Peer-to-Peer NFT Loans
  - Peer-to-Peer Crypto Loans
  - Real-Time Oracle Data for Loans
  - Automatic Liquidation Options
  - NFT Holder Utility
  - Peer-to-Peer Risk Management
  - User-Friendly Dashboard
  
## Chart flow

![Chart flow](https://i.imgur.com/vRq7nAN.png)

### Further development

  - Improve external contract calls.
  - Minimize gas cost.
  - Create more investors protection.

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

### Development

Want to contribute? Great!

# Authors

        Smokish
        Email - loansonape@gmail.com
      

# Acknowledgments

    Apes on Ape - https://apesonape.io/
    Apes on Ape Arcade - arcade.apesonape.io

# License

  MIT

