# Layers-in-blockchains
Before deep diving into blockchain layers, there is a need to understand the role of various layers.

### First of all, let's talk about Blockchain Trilemma

Blockchain trilemma
Tri means three so according to this every blockchain should have three pillars

- Scalability

- Security

- Decentralization

#### Scalability
This means the blockchain should be capable of processing the maximum number of transactions possible. 
If the blockchain is not able to process many transactions then that blockchain cannot be much scalable.


#### Security

The most important pillar every blockchain should have is security.
It is crucial to know whether the blockchain is secure or not. 

#### Decentralization

So now, the blockchain is scalable and secured. But if it is not decentralized which means it is controlled by some central authority then it would be a simple database rather than a blockchain.



# OK, Nice!

#### But is it possible to achieve each pillar 100%?

So here comes the idea of the cap theorem 

According to this theorem, any blockchain could achieve only 2 pillars with 100% efficiency. So, out of three pillars, the blockchain can be scalable and secure but not decentralized. Or, decentralized and secure but not scalable.


For example- Bitcoin is one of the blockchains which is decentralized and secure(as it follows a proof of work algorithm) but it is not scalable because bitcoin can perform only 4-5 transactions at a time.

#### Cap theorem is just a theorem like other mathematical theorems so it can be proved wrong.

Thus the blockchains these days are made in such a way that they are all 3! "scalable, secure, and decentralized".
So Blockchain developers try to achieve 100% of all the pillars of blockchain to prove the cap theorem wrong.

### This orginated concept of Layers 
These layers help to make our blockchain secure, scalable, and decentralized.

There are four layers of blockchain:- 

                                                Layer3
                                                Layer2
                                                Layer1
                                                Layer0.

Every layer has its own functionality

To understand layers in simple language we can say that these are the program script written to describe some functionality of that blockchain
This means layer0 is just a program written describing some functionality 

## Layer 0

This layer gives all the basic features a real blockchain should have.

Form capability means:-

- Allowing one blockchain to interact with another
- How transactions would take place
- How the blockchain would connect to the internet, how it will use hardware
- How developers would be able to develop smart contracts 

So all these things come under layer 0, which means it provides fundamentals to the blockchain.


## Layer 1

Layer 1 is just above layer 0

### This provides security to the blockchain

- Layer 1 blockchain like Bitcoin employs a proof of work consensus mechanism which involves miners solving complex mathematical problems to add a new transaction to the blockchain

Layer1 prioritized decentralization and security so developers were inspired to modify the design to prioritize scaling as well

Some of the ways by which L1 could prioritize scaling as well:-

- Increasing size of block- size of the block could be increased so that it could accommodate more transactions
But the problem is that blocks need to be transferred to other nodes as the blockchain is distributed network and transferring large blocks would take more time
- Adding whole data in a block (basic protocol of blockchain)- adding some data to the database will also not work as security would not be achieved due to interference of central authority
Thus due to these limitations of L1 blockchain design was improved and L2 (layer2) was built on top of L1.

## Layer 2
Then comes layer 2 which is much more important than the other layers.

This is very important because it deals with the scalability of blockchain and till now existing blockchains have achieved perfect layer0 and layer1 but none has a good layer2.

For example- polygon uses layer2 that's why it is fast and much more scalable than any other network. It is just because of layer 2. They increase the speed of transactions that is scalability by executing some transactions off-chain and only some transactions are performed on-chain to finalize the results.

Layer 2 blockchain has a different scaling solution from layer 1 and this includes: State channels, Sidechains, and Rollups:-

- State channels- the most famous example of this is the bitcoin lightning network In this users can do micro-transactions between themselves, afterward, the final state of the transaction is added to the blockchain

- Sidechains - Sidechain transactions are off the main chain but are publicly recorded, unlike private state channels, Sidechains have their miners and are responsible for their security
-  Rollups -They take the transactions out of the mainnet and process them off-chain, convert them into one single piece of data, and submit them back to the Ethereum mainnet and it is possible to verify rollup’s

Two major examples of layer 2 solutions are the Bitcoin Lightning Network and the Ethereum Plasma. Despite having their working mechanisms and particularities, both solutions are striving to provide increased throughput to blockchain systems. 

### So here there is more focus on layer 2 with help of the bitcoin lightning network concept:-

Bitcoin lightning network is a layer2 solution for bitcoin because as discussed above bitcoin is not as scalable as a polygon which means this network makes our bitcoin faster 
To understand more about the bitcoin lightning network concept let's see an example

So let us say Raju wants to buy a coffee from Pinki and did the transaction in crypto now the problem is that the transaction may take hours to get processed.
So payment channel is the solution:-

Payment channel uses 

- Multisignature
- Time lock
Example:

- This means Raju and Pinki will create a payment channel and will digitally sign it.

- Now as a payment channel is created Raju needs to fund this channel, say Raju gave 1 BTC to this channel.

- This transaction of Raju will be stored on the bitcoin network and this transaction is called the funding of the transaction.

- After that let's say Raju buys coffee for 0.1 BTC for the next few days so that transactions will not be recorded on the bitcoin network.

- Now Raju was bored with coffee so he decided not to buy anymore.
Thus at this point, the transaction included 0.6 BTC left with Raju as he drank coffee of 0.4 BTC. So Raju will close the payment channel and 0.4 BTC will be transferred to Pinki.

### Note- Anyone either Raju or Pinki could close the payment channel whenever needed.


Thus from the above example, it could be made clear that Layer 2 protocols provide a second framework where transactions can take place separately from layer 1. This means that a great portion of the work that would be performed by the main chain can be moved to the second layer. So while the main chain (layer 1) provides security, the second layer offers high throughput, being able to perform hundreds, or even thousands, of transactions per second.


## Layer3
- It focus on UI interface means how easily users can use your blockchain

- Most important of all, layer 3 networks help in interconnecting different aspects of the blockchain and web3 landscape to enable communications between them. 

- This enables apps, games, distributed storage, and other applications built on top of a blockchain platform to function properly.
Without these applications, Layer 1 protocols alone would be quite limited in usefulness Layer 3 is essential for unlocking their power.

Thus Layer 3 protocols provide instructions that allow users to access applications built on top of the entire system. Together, these elements all contribute to creating a powerful trustless infrastructure capable of handling large-scale transactions securely.



