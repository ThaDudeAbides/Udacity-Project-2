# ND1309 C2 Ethereum Smart Contracts, Tokens and Dapps - Project Starter 
**PROJECT: Decentralized Star Notary Service Project** - For this project, you will create a DApp by adding functionality with your smart contract and deploy it on the public testnet.

#  Welcome

Thank you for reviewing my implementation of the StarNotary smart contract.

## ERC-721 Names

The name of this ERC-721 Token is: "THE Awesome Star Token"
The symbol for this ERC-721 Token is: "AST"

## Version Information:

Truffle version used:  5.3.10
OpenZeppelin version used:  2.3

### Other Versions Used:
** NOTE:  Used 'nodeenv' to apply appropriate Node.js version 10.19.0 to comply with class boilerplate code
Node version:  10.19.0
NPM version:  6.13.4
Metamask version:  9.6.1
Truffle HD Wallet version:  1.0.17

## Deployment to Rinkeby

Below are details related to the deployment of the StarNotary smart contract to the Rinkeby network.

### Truffle Migrate Command Line Output

Starting migrations...
======================
> Network name:    'rinkeby'
> Network id:      4
> Block gas limit: 10000000 (0x989680)


1_initial_migration.js
======================

   Replacing 'Migrations'
   ----------------------
   > transaction hash:    0xa56826e33e66562e0dd82859553e9759661ebf584b1e559eefdfbaf6de6b93ef
   > Blocks: 0            Seconds: 12
   > contract address:    0x631566ABe8bdd00F73ddfD87427f4Ee47cc4D2D0
   > block number:        8805241
   > block timestamp:     1624315059
   > account:             0xE755Be65d4e24E64e173320D9b4Fd202E430E6AC
   > balance:             18.721139732
   > gas used:            226537 (0x374e9)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.00226537 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.00226537 ETH


2_deploy_contracts.js
=====================

   Replacing 'StarNotary'
   ----------------------
   > transaction hash:    0x79c9e12f09be4f027315754b24686dbe6ec9389bd771a6e5b775df6d83f97a71
   > Blocks: 0            Seconds: 12
   > contract address:    0xE05F2bb368A922af9F899295d936f053479c38C7
   > block number:        8805243
   > block timestamp:     1624315089
   > account:             0xE755Be65d4e24E64e173320D9b4Fd202E430E6AC
   > balance:             18.697527982
   > gas used:            2315412 (0x235494)
   > gas price:           10 gwei
   > value sent:          0 ETH
   > total cost:          0.02315412 ETH


   > Saving migration to chain.
   > Saving artifacts
   -------------------------------------
   > Total cost:          0.02315412 ETH


Summary
=======
> Total deployments:   2
> Final cost:          0.02541949 ETH

### Verification That the Contract Exists on Rinkeby

See Contract Hash on rinkeby.etherscan.io:  https://rinkeby.etherscan.io/address/0xE05F2bb368A922af9F899295d936f053479c38C7

### Testing Creating Star on Rinkeby

Created Star called 'test' at ID=1
See transaction hash on rinkeby.etherscan.io:  https://rinkeby.etherscan.io/tx/0xa749b5bc8d93377f426bafc3846d7055ffbb9d31930393c7d22ab8f3fee9307f

Created Star called 'asdf' at ID=2
See transaction hash on rinkeby.etherscan.io:  https://rinkeby.etherscan.io/tx/0x3e739822a9e85326300a2629f4aed912897334a0095dc8ba840dfc7bc8adfb37

