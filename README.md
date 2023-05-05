# What is ForeverPFP?
ForverPFP is a project build by some contracts to connecting web3 people onchain.

# [PrimaryPFP](https://github.com/ForeverPFP/contract/blob/main/src/IPrimaryPFP.sol)
Bind your primary PFP to an address like [Primary ENS Name](https://app.ens.domains/faq#what-is-a-primary-ens-name-record).
By binding your primary PFP to your address, if you set twitter account in your primary ENS for the same address, we can make you find your PFP community members twitter accounts by onchain data.

PFP holder can have more than one PFPs in one address, but for the social networking better knowing your "face", it would be better choose a primary PFP by binding it.

## Why PrimaryPFP instead of ENS Avatar?

We can [set avatar in ENS](https://medium.com/@brantly.eth/step-by-step-guide-to-setting-an-nft-as-your-ens-profile-avatar-3562d39567fc), but without ownership verification, you can set other people's PFP image, PrimaryPFP verify the ownership to make data right.

We have getName(address) function provided by ENS now, we will have getPFP(address) function by PrimaryPFP, with this you can easy to get your Ethereum ID(ENS name and PFP image) anywhere with one ethereum address signed to login.

## How to find PFP community members easier by this project?

Bind your PFP to your ENS, set twitter account in your ENS, a website will be developed to show all the binding PFPs and their twitter accounts to connect the web3 people by onchain data.

## Any fee binding/unbiding my PFP?

There is no fee for unbinding. The fee for binding is 0.01 ETH, discussion is [here](https://github.com/orgs/PrimaryPFP/discussions/14).

## Where is the money paid goes?

The money goes to the PFP DAO Treasury maintained by a group of people.

## Can I rebinding PFP to another address?

Yes, you can rebinding your PFP to any address anytime by your token owner address.

## What is bind delegate?

It worked the same way like delegate.cash, you can bind your PFP to an delegate address which can be a hotwallet to avoid scammed by signing.
The best practice would be set your ENS primary name to a hotwallet, and bind your primary PFP delegate to the hotwallet.

## How can I unbind the delegate?

Unbind by owner or bind/delegate to a new address is the way to unbind a delegate.

## What if I sold my Primary PFP?

The binding data is still in the contract if the new owner don't override it.

## Can I use the PrimaryPFP if my PFP collection is not verified by the community?

Yes.

# [PFPVerification](https://github.com/ForeverPFP/contract/blob/main/src/IPFPVerification.sol)

A PFP verification list maintained by the community to avoid PFP image copycats.

Right now the PFP verification is done by opensea and twitter, but sometimes you may fooled by the verified PFP project with same image copy from bluechips with different background colors like [RRBAYC](https://etherscan.io/address/0x2ee6af0dff3a1ce3f7e3414c52c48fd50d73691e) or [v1cryptopunks](https://etherscan.io/address/0x282bdd42f4eb70e7a9d9f40c8fea0825b7f68c5d), unique PFPs collection list should be maintained by the community instead of centralized company.

## Any token in the future for ForeverPFP?

Community can make the decision in the future ERC721 or ERC20 token for governance.
