# flashloan
Running through truffle box flashloan tutorial


https://www.trufflesuite.com/boxes/flashloan-box


https://docs.aave.com/developers/v/1.0/deployed-contracts/deployed-contract-instances

DAI address => 0xf80a32a835f79d7787e8a8ee5721d0feafd78108


Faucet => https://faucet.dimensions.network/

contract address => 0xe860621aCEF7499828d8D095684D30466d076335

Script to do flashloan
- let f = await Flashloan.deployed()
- asset = '0xFf795577d9AC8bD7D90Ee22b6C1703490b6512FD'
- amount = web3.utils.toWei('1000')
- f.flashloan(asset, amount)


https://kovan.etherscan.io/tx/0xfec5ab560d9078a58211f377470e88f1c5c652c5a005272ea34305ae424df2db


Remember to load deployed contract with funds