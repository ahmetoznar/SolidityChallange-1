# Solidity Challange #1


Hello everyone, I decided to create a challenge to improve this ecosystem and increase the knowledge of the developers in the ecosystem.


In this challenge, I handle a not-so-known method that I see frequently among the requirements of companies hiring for smart contract developers, and which I have heard about recently.
If you are successful in the challenge, you can claim 300 USD from the smart contract.


# Problem -


Suppose you have a hacked wallet, and the attacker only sends Ether from your wallet to their address, but you have 300k USD worth of DAI in your wallet. 

And when you send Ether to the wallet to get back DAI tokens, the attacker sends Ether to their own address, thanks to a bot they set up.

In this case, how do you get DAI tokens from the wallet in the most secure way?

Note: Assume you don't have an RPC faster than the attacker's RPC.

`Private key of the hacked wallet:`

`Contract address of the token stuck in the wallet:`

`Contract address to claim the prize:`


The first person who transfers the token from the wallet and calls the "getReward" function in the Reward contract receives 300 USD.


Also, I would like to know how many people are currently dealing with this problem. 

So if you intend to solve the problem, you should give your address as a participant in the contract before April 5. To do this, you need to interact with the "participate" function in the reward contract.
Who participant at reward contract can claim only. 


Additional Note: Don't try to cheat by sending Ether to hacked wallet, Ethers which is sent to hacked wallet will be transferred to another wallet. And will not be refunded.
