+++
author = "Joe Viveiros"
categories = ["blockchain"]
date = 2022-03-03T14:00:00Z
description = "New blocks are always stored linearly & chronologically. This means that they are always added to the “end” of the blockchain."
image = ""
title = "Is Blockchain Secure?"
type = "post"

+++
Blockchain technology accounts for the issues of security & trust in a few ways.

To begin with, new blocks are always stored linearly & chronologically. This means that they are always added to the “end” of the blockchain. If you ever bother to take a look at Bitcoin’s blockchain, you’ll see that each block has a position on the chain, called a “height.” As of January 2020, the block’s height had reached 615,400.

After a block has been added to the end of the blockchain, it’s almost impossible to go back & edit the contents of the block. That’s because each block contains its own unique hash, as well as the hash of the block before it. Hash codes are created by a mathematical function that converts digital information into a string of numbers & letters. If that information is edited in any way, then the hash code changes as well.

Here’s why that’s important to security. Let’s say someone try’s to edit a transaction so that you would have to pay for something twice. As soon as they edit the $ amount of a transaction, the block’s hash will also change. The next block in the chain will still contain the old hash, & they would need to update that block in order to cover their tracks. However, doing so would change that block’s hash. & the next, & so on.

In order to change a single block, then, someone would need to change every single block after it on the blockchain. Recalculating all those hashes would take a huge & would require an improbable amount of computing power. So, once a block is added to the blockchain it becomes extremely difficult to edit & impossible to delete.

To further address the issue of trust, blockchain networks have implemented a series of tests for computers that request to join & add blocks to the chain. The tests, called “consensus models,” users are required to “prove” themselves before they can participate in a blockchain network. One of the most common examples employed by Bitcoin is called “proof of work.”

## Proof of Work

In the proof of work system, computers must “prove” that they have done “work” by solving a complex computational math problem. If a computer solves one of these problems, they become eligible to add a block to the blockchain. But the process of adding blocks to the blockchain, what the cryptocurrency world calls “mining,” is not easy. The odds of solving one of these problems on the Bitcoin network were roughly one in 15.5 trillion in January 2020.1 To solve complex math problems at those odds, computers must run programs that cost them significant amounts of power & energy.

Proof of work does not make attacks by hackers impossible, but it does make them practically useless. If someone, for some reason, wanted to coordinate an attack on the blockchain, they would need to control more than 50% of all computing power on the blockchain, so that they would be able to overwhelm all other participants in the network. Given the tremendous size of the Bitcoin blockchain, a so-called 51% attack is almost certainly not worth the effort & more than likely impossible.