# Udacity Blockchain Capstone

The capstone will build upon the knowledge you have gained in the course in order to build a decentralized housing product. 

**Getting Started**

Prequisites

For development make sure ganache-cli is installed globally,metamask extension is enabled and solidity compiler is configured in truffle config.

Install Dependencies

    Install all requisite npm packages

npm install

Dependencies Version

* Truffle v5.1.25 (core: 5.1.25)

* Solidity - 0.5.8 (solc-js)

* Node v10.18.0

* Web3.js v1.2.1


**Run and deploy on rinkeby**

cd eth-contracts 

truffle migrate --network rinkeby --reset --compile-all

    Contract address is witten to config.json

**Mint Tokens**

    Inside eth-contracts folder, Run

node addSolution.js ../zokrates/code/square/proofs/proof<number>.json <tokenId>

node mintToken.js <tokenId>


**OpenSea MarketPlace**

    Get your contract listed on https://rinkeby.opensea.io/get-listed/step-two

**Project Deliverables**

* Contract Address and ABI

View the contracts on etherscan

  * Verifier at 0x40751D2195B07D8F4C191A9AAeB539dBe326DD48
  
  * SolnSquareVerifier at 0x396D70D8Fd7d6de842d9A5deae046575AD6c39d6


* **OpenSea Market Place -** https://rinkeby.opensea.io/assets/unidentified-contract-v373


![](images/Screenshot(251).png)


# Project Resources

* [Remix - Solidity IDE](https://remix.ethereum.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Truffle Framework](https://truffleframework.com/)
* [Ganache - One Click Blockchain](https://truffleframework.com/ganache)
* [Open Zeppelin ](https://openzeppelin.org/)
* [Interactive zero knowledge 3-colorability demonstration](http://web.mit.edu/~ezyang/Public/graph/svg.html)
* [Docker](https://docs.docker.com/install/)
* [ZoKrates](https://github.com/Zokrates/ZoKrates)
