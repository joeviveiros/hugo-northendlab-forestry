+++
author = "Joe Viveiros"
categories = []
date = 2022-03-01T14:00:00Z
description = "The best definition for this technology - it is a distributed, decentralised, public ledger. digital information block stored in a database “chain”."
draft = true
image = ""
title = "How Blockchain Works"
type = "post"

+++
Whenever a block stores new data it’s added to the blockchain. Blockchain, as the name suggests, is made up of multiple blocks that are all strung together. Now, in order for a block to be added to the blockchain, four things need to happen:

* A transaction must occur. Let’s continue with an example of an online purchase, any & all online purchases. After clicking through multiple checkouts prompts, you finally complete the purchase. In a lot of cases, a block will group together potentially thousands of transactions, so your online purchase will be packaged in the block along with other users’ transaction information, also.
* That transaction must be verified. After making a purchase, your transaction must be verified. With other public records of information, like Wikipedia, the ATO, even your local library, there’s someone in charge of vetting new data entries. With blockchain, however, that job is processed by a network of computers. When you make your purchase, that network of computers checks that your transaction happened in the way you said it did. Specifically, they confirm the details of the purchase, including the $ amount, the time that the transaction’s occurred, and the participants.
* That transaction must be stored in a block. After your transaction has been verified as accurate, it gets the proverbial green light. The transaction’s $ amount, your digital signature, and the vendor's digital signature are all stored in a block. There, the transaction will join hundreds, or thousands, of others just like it.
* That block must be given a hash. What's a hash? Once all of a block’s transactions have been verified, it must be given a unique, identifying code called a hash. The block is also given the hash of the most recent block added to the blockchain. Once hashed, the block can then be added to the blockchain.

When that new block is added to the blockchain, it can become publicly available for anyone to view — including you. If you ever take a look at Bitcoin’s blockchain, you will see that you have access to transaction data, along with information about when (“Time”), where (“Height”), and by who (“Relayed By”) the block was added to the blockchain.