# Introducing "Fonduels" a new project built on Enigma

## Slow down there cheeze whiz, what's this Enigma?

> Enigma is a decentralized, open-source protocol that lets anyone perform computations on encrypted data, bringing privacy to smart contracts and public blockchains. Our mission: improve the adoption and usability of decentralized technologies, for the benefit of all.

** That's cool but what's it got to do with blockchain games?

So glad you asked 😊

Imagine a turn based game processed a public blockchain like Ethereum where two players battle each other. The game works by each player submitting choices to a smart contract. The game contract takes those moves, processes them according to the game's logic, and declares one of the players victorious. Since the game is processed on Ethereum turns would be public to anyone who wants to see them, including your opponent who might be watching and waiting for your moves to cheat the outcome. To prevent snooping on our tactics, we'll have our game encrypt the moves it uploads to the blockchain and wait for both players to submit moves before revealing them publicly. This reveal commitment is a second transaction and some extra logic might be required to automatically process a game result in case only player decides to reveal. This could happen if the second player sees they already see lost, because of what player 1 revealed, and is being a bit of a sore loser 🥊 

![](https://github.com/Cheeze-Of-Insight/coi-blog/blob/master/posts/feb2_2020/assets/gameover.png)

While the above definitely works, it's adding an extra step of transactions, for each player, and comes at a cost of some time out logic to pad against the bruised egos of bad sportsmanship 😄 Since the above logic applies to a wide variety of games, it would be boon to the community if we could somehow rid ourselves of this second stage of (reveal) transactions entirely...

And really, that's what Fonduels is all about.

![](https://github.com/Cheeze-Of-Insight/coi-blog/blob/master/posts/feb2_2020/assets/fonduels.png)

## Let the Fonduels begin!

We certainly noticed how the reveal stage of game play effected the play experience the Cheeze Wizards game from Dapper Labs. In Cheeze Wizards if a player refused to reveal their moves, the two NFTs in question would be locked in a battle for 90 minutes until the automatic duel time out function would finally kick in and process the game result. Because Cheeze Wizards fight windows lasted for only three hours with about 4 hours between windows, most NFTs involved timed out duels won't get to battle again until the next fight window (even though a smoothly coordinated duel might typically settle in as fast as 15 to 20 minutes).

![](https://medium.com/dapperlabs/a-step-by-step-walkthrough-of-a-cheeze-wizards-duel-b262701792e5)

With all of this in mind our team travelled to ETH Waterloo II and created Fonduels. 

[ethwaterloo2.jpg]

> Enigma is a [decentralized] secure computation network that acts as a layer 2 solution for Ethereum. Enigma introduces the concept of secret contracts, which are identical to Ethereum contracts but can compute on sensitive data.

By processing reveal transactions in an Enigma secret contract, we created a modified version of the Cheeze Wizards game that eliminated the second stage of reveal transactions and removed the need for resolving timed out duels. This provided players with a lightning quick gameplay experience at a minimum of 50% faster dueling and zero risk of duels timing out.

![](https://devpost.com/software/fonduels)

## What's next for Fonduels?

We're excited by the opportunities Enigma has to offer driven crypto games. Now that we know what's possible we're rebuilding Fonduels into a general platform that can be used by any turn based blockchain game requiring committing and revealing encrypted turns.

![](https://github.com/Chain-of-Insight/fonduels)

With our new game *Satohis's Lost Faucet* just getting ready for launch (see: ![](https://twitter.com/chainofinsight/status/1218663910120792065)), Fonduels has moved up to our top priority. 

Stay tuned! 😊

![](https://github.com/Cheeze-Of-Insight/coi-blog/blob/master/posts/feb2_2020/assets/shallweplayagame.jpg)




