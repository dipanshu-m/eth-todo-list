# ETH-TODO-LIST

Setup and run locally:

`npm install`

Check truffle version:

`truffle version`

If not installed, type:

`npm i -g truffle@5.0.2`

To compile truffle project:

`truffle compile`

To migrate and put the contract on blockchain:

`truffle migrate`

Note:

1) Check the truffle-config.json file, the port must match with the ganache running locally
2) Install ganache and run in quickstart from official truffle framework website. Match the ganache ports and localhost with truffle-config.json file in networks>development
3) Files in migrations are run serially, so, to run it in second order, name it: 2_xxx.js
4) First compile, then migrate. Migrate is kind of like deploying contract in blockchain
5)
