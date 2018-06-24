# NIP-1
A new monetary policy to increase blockchain banking friendliness and market price stability
 
# Simple Summary
A new monetary policy which controls the amount and velocity of market can lead to a more vivid, stable, innovative and banking friendly system.

# Abstract
This NIP will propose a new monetary policy through a new hard fork. The main purpose of this new policy is making Nilu a better “Blockchain Based Banking Backend” in one hand and controlling velocity and volume of coins in the market to save the interests of Nilu holders and miners against short-sight seasonal miners in other hand. By decreasing miner reward to 6 NILU and allocating 2 NILU to holders (All nilu holders who deposits their money in a special contract), a proof of deposit policy can be added to Nilu. Adding this policy, we can make a potential benefit for DApps which focusing on holding money for a period of time. This will make Nilu a good and attractive platform for wide range of blockchain based businesses, specially banking and payment facilitation style services. POD also helps in making a more stable market and fair prices. 
On this proof of deposit system, a MetaBank smart contract will gain 2 NILU for each mined block and 99.8% of this reward will be distributed to NILU depositors based on their shares in each 30,000 Block. Other 0.2% part will be paid to heralds. The first 8 persons who inform smart contract about settlement time in each 30,000 blocks.
 
# Motivation
As a newly launched Ethash based and pure POW cryptocurrency and smart contract platform, there are two big challenges ahead, attracting users and developers to use this platform as an smart contract and DApp backend (specially banking dapps in Nilu case) and overcome pure POW sourced issues. Because of the amount of coin supply and velocity which is not balanced with the exchange size, a pure POW network could be more vulnerable and affected by short-sight miners, market dumpers and even some big holders.
It required to make Nilu a more attractive platform for developers and businesses and also save benefits of long-sight holders and miners against market instability. Rewarding holders in a proper manner, can create a potential for some different blockchain based business models and owners and save benefits of Nilu community members.
 
# Specification
1. An smart contract, named Meta Bank, to be earned 2 NILU per block. Means that for each block, 2 NILU will added to Meta Bank’s account. Other 6 NILU will rewarded to the block miner.
2. Metabank can accept time deposits equal or bigger than 50,000 NILU, both regular address and contracts accepted. By accepting contracts we can expand Metabank functionality and also give chance to developers to develop their own contracts for playing the bank role, for example dapps with different interest rate and deposit limit, or dapps for giving loan and so on.
3. Deposits will be blocked during period of 30,000 blocks called “Deposit round”.
4. Each depositor will get interest based on its share in total blocked amount. No interest will give to deposits for part of a deposit round. So, if a wallet deposit some Nilu on block 12,000 of a deposit round, no interest will give to this wallet for the remaining 18,000 blocks. But it will get interest at the end of the next deposit round, and all rounds after. (For sure in case of keeping Nilu on Metabank)
5. All withdrawal requests submitted between a deposit round period, will be processed for payment the beginning of the next block.
6. At the end of each deposit round, 99.8% of that rounds reward equal to 59,880 NILU will be distributed between depositors based on their blocked deposit amount.
7. At the end of each deposit round which is actually one block before starting of the next round, smart contract should be started to run its tasks and distribute bank account owners’ profit. This action should be triggered by “Herald” (herald can be regular addresses or smart contracts). 0.2% of that round’s reward equal to 120 NILU will be distributed between the first 8 heralds.

Above parameters can be changed in the future based on the community votes. For instance, Increasing POD share by time. Moreover, this policy has no conflict with POS rewarding system. So, we can potentially have a network with 3 rewarding rules to fulfill different aspects of a good cryptocurrency and smart contract platform POW, POD and POS. 

# Rationale
Giving reward for holding NILU and slowing down the velocity, can make some novel and exquisite potentials for new types of business models, specially for banking style business. For example, a second level smart contract based bank can serve to deposits with lower balance, or a service for free but delayed transfer of Nilu will be imaginable with this new model.
This change also will encourage Nilu holders to keep their Nilu out of the market and get some reward instead. Controlling the velocity and volume of market can lead to a more stable network and community. In current situation, some short sight miners or pump and dumpers may have opportunities to affect the market and also the community through that. Decreasing miner reward and reserving some reward for long-sight Nilu owners, i.e. Holders or in other word “loyal members of the community”.

 
# Backwards Compatibility
This NIP is consensus incompatible with the current Nilu chain and would cause a hard fork when enacted.
