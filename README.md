# flashloan
Running through truffle box flashloan tutorial


https://www.trufflesuite.com/boxes/flashloan-box


https://docs.aave.com/developers/v/1.0/deployed-contracts/deployed-contract-instances

DAI address => 0xf80a32a835f79d7787e8a8ee5721d0feafd78108


Faucet => https://faucet.dimensions.network/

contract address => 0x5244262e7b9Ed382C8CE5FF0944044Fb34FF98d9

Script to do flashloan
- let f = await Flashloan.deployed()
- asset = '0xFf795577d9AC8bD7D90Ee22b6C1703490b6512FD'
- amount = web3.utils.toWei('1000')
- f.flashloan(asset, amount)