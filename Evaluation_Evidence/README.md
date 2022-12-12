# Solidity Smart Contract Execution Results

<p align="center">
  <img src="./../Images/crypto.png"/>
</p>

---

## Short Clip Demonstrating the Execution of Purchasing KaseiCoin

https://user-images.githubusercontent.com/108703181/207176948-c3cec577-5f70-4054-8b33-0fe94568902f.mp4

* The video above demostrates how to compile and run the following solidity files:

    * [KaseiCoin.sol](./../KaseiCoin.sol)
    * [KaseiCoinCrowdsale.sol](./../KaseiCoinCrowdsale.sol)

---

## Things to Note:

<b>The goal is to create a fungible token that is ERC-20 compliant and launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin (KAI).</b>

* Smart Contracts Created:

    * KaseiCoin Token Contract
    * KaseiCoin Crowdsale Contract
    * KaseiCoin Crowdsale Deployer Contract

> **Note:** The KaseiCoin Crowdsale contract utilizes additional libraries from OpenZepplin to extend the functionality of the contract by adding time restrictions, refund capablities, and a cap for the number of tokens that can be created. In the video above, you can see that there is a cap of 50 ETH being placed into the contract, indicating the maximum amount of funds wanting to be raised. The time restriction is also integrating into the crowdsale which is set to 5 minutes after executing the crowdsale contract. The contract owner has the ability to refund user funds only when the crowdsales time restriction ends and if the cap goal is not satisfied. 