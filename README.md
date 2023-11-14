# Smart-contract-Lottery-Project
The rapid evolution of blockchain technology has led to transformative changes in various industries, and the gambling sector is no exception. This repo delves into the concept of a "Smart Contract Lottery," exploring its potential impact on transparency, security, and trust in the realm of online gambling. As traditional lottery systems often face challenges related to fairness and accountability, the integration of smart contracts aims to provide a decentralized, tamper-proof, and transparent solution.

First of all, we need install node.js and npm because our project is in a python environment:

For install the brownie using node.js command prompt we write this command: pip install eth-brownie
![image](https://github.com/ddeeona/Smart-contract-Lottery-Project/assets/147994845/0620d845-d974-4026-847a-29ea1c742e9e)
![image](https://github.com/ddeeona/Smart-contract-Lottery-Project/assets/147994845/d1417989-904d-490a-b594-707af384ed9a)


Deploy to a testnet: brownie run scripts/1_deploy_lottery.py

There are 2 types of tests in this project: unit tests, which run on a local blockchain; integration tests, which run on a testnet

To run the unit tests: brownie test 

Integration tests: brownie test --network <network>	
