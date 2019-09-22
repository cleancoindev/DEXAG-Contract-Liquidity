# DEXAG-Contract-Liquidity

This repo is an example of a smart contract utilizing the DEX.AG API and Proxy Contract for Contract Fillable Liquidity. The main contract is `BuyAndSend.sol` which is a contract that allows a user to send any ERC20 token to another ethereum address without having to hold that token or store them in the contract. To deploy the contract using this repo, the only thing you'll need is truffle installed on your system. Inside the `migrations` folder in the `2_deploy_contracts.js` file, set the `proxy` variable to the address of your DEX.AG proxy contract and then run `truffle migrate` from the root of the directory.
