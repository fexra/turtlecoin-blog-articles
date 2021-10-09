# TRTL v2

Oct 23, 2020

---

![](./images/0fBCSto8YQMvzbsD9.png)

_Have a seat, pour a cup of whatever drink you celebrate with, and think about where you left those old TRTL wallet keys. Whether you like what we say next or not, you’re going to need them, soon.._

## My friends, it is time for us to say goodbye.

Today we hit block 3,000,000\. We upgraded our network and our proof of work algorithm for the last time. By block 4,000,000 or in about 1 year from today, the TurtleCoin network as we know it will begin on a path of its own destruction.

A short time after block 5 million, the chain will be dead, and completely gone, unable to produce more blocks.

**Don’t panic, we have a plan.** I said this would be celebrating :)

Sometimes you have to know when it is time to move on, and for us the time is now. Starting today we will be freezing the main core software repository. In the year that follows we will be writing code, documentation, and testing the new software we are already building for TRTL v2.

The next iteration of the software will work best with a blank slate to allow us to improve the network based on the things we learned in our current software. The main changes are:

* Chain relaunch near December 2021
* Coin swap w/ reverse split
* Fair proof of stake
* New core software

Let’s look into each one of those points and explain what is happening from a high level.

## Chain Relaunch

Launching with a fresh chain on new software will enable us to be more flexible in the things we can make the new network do. If we have to operate with the constraints of backward compatibility, we will have to write a lot of code twice and basically build another version of what we have now, instead of something completely new.

## Coin Swap w/ Split

Despite having a low emission atomically, our transactions average a large number of inputs. A lot of these smaller inputs now become smaller than the cost of handling them, so we call them “dust”. Think of how many handfuls of pennies you would need to pay for lunch.

To cut down on this dust, we will be reducing our supply by 100,000:1.

If you currently have 10,000,000.00 TRTL on the old chain, on the new chain you will have 100.00 TRTL. If you have 1,000,000 on the old chain, on the new chain you will have 10.00 TRTL. We will be keeping the 2 digits after the decimal point and will be keeping the TRTL ticker and wallet prefix.

The new total supply of TRTL will go from 1 Trillion (1,000,000,000,000.00 TRTL) to 10 Million (10,000,000.00 TRTL).

![](./images/0VF-BX-ChDHB4OCVK.png)

If you have <1,000 TRTL today, you will have 0 TRTL on the new chain.

The swap will be organized via a website that takes your new wallet address and helps move your coins to the v2 chain. When the swap is complete and the old TRTL chain is dead, the funds will be burned, and the excess funds left unclaimed will go out in staking rewards on the new chain.

## Proof of Stake

We don’t have a fancy name for it yet, but we have designed a system that could kind of be compared to proof of stake, but it still has a little proof of work sprinkled on top.

TL;DR — There will be staking. There will be no more proof of work for mining.

We have developed an algorithm in-house that involves staking and uses a fair system for selecting block producers where whales have a hard time dominating production without significant cost. To cut down on spam and wasteful transactions, we are using proof of work to derive a proof of importance for each transaction, offering a user the option to compute more rounds of work to lower the fee, or pay a higher fee to send more rapid transactions.

The end result is a block chain that consumes less resources, is less centralized, and incentivizes good peers to stay online and provide good network throughput as we grow in volume. On the new network, there are no empty blocks, either.

## New Core

We have already started specifying and building the new core protocols. It made sense to keep the modular approach of daemon+wallet, so starting with the daemon, we are writing it all from scratch. While this means we will no longer be a CryptoNote project, we will still have privacy the way we do now, and with the added bonus of not being a fork of anything, as that seems to bother some people.

Part of focusing all our efforts on the new core suite is to stop slapping duct tape on the old code base. From this point forward, there will be no new features, enhancements, or active development on the current repository. We will, however, review and address any critical issues and bug fixes that are required to keep the network in stable operation. In due time, you will find the current repository archived and read only once we are ready to nail the coffin closed via a consensus mechanism that brings the current chain to its final resting place.

We hope to be able to testnet the new network daemon soon, and I am sure we will need testers when we are ready, so if you have Discord, pop on by the TurtleCoin Discord and let us know so we can put you on a list of testers for when the time comes.

_Until then, take care, we look forward to another 3 years with you all :)_

**TurtleCoin® Core Team**

_Originally published at_ [_TurtleCoin_](http://blog.turtlecoin.lol/archives/trtl-v2/)_._