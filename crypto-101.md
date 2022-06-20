# 💲 Crypto 101

![](<.gitbook/assets/Screen Shot 2022-06-19 at 1.02.50 PM (2).png>)

## 💲 Crypto 101

Understanding the following information is not necessary to [mine](helium-glossary.md#mining) [HNT](helium-glossary.md#hnt), but until it’s [exchanged](helium-glossary.md#exchange) for [fiat](helium-glossary.md#fiat), the [crypto](helium-glossary.md#crypto) in your [wallet](helium-glossary.md#crypto-wallet) represents [stock](helium-glossary.md#stock) in the affiliated [software](helium-glossary.md#software). Developing a more well rounded perspective of what makes [Helium](helium-glossary.md#helium) work may give you a better idea of why exactly it is you’re in the space, and just what makes it so exciting!

_Below are some really fundamental principles behind_ [_blockchain_](helium-glossary.md#blockchain)_,_ [_cryptocurrency_](helium-glossary.md#cryptocurrency)_, and what exactly makes_ [_digital money_](helium-glossary.md#digital-currency) _work._

[_**What is money?**_](crypto-101.md#what-is-money)

[_Cryptocurrency_](crypto-101.md#cryptocurrency)

[_Centralized vs. Decentralized_](crypto-101.md#centralized-vs.-decentralized)

[_What is Blockchain?_](crypto-101.md#what-is-blockchain)

[_What is a Hash Function?_](crypto-101.md#what-is-a-hash-function)

[_Immutability_](crypto-101.md#immutability)

[_What is a Consensus Mechanism?_](crypto-101.md#what-is-a-consensus-mechanism)

[_What is DeFi?_](crypto-101.md#what-is-defi)

[_Scarcity_](crypto-101.md#scarcity)

### _What is_ [_Money_](helium-glossary.md#money)_?_

[Money](helium-glossary.md#money) can be defined as anything that is both [scarce](helium-glossary.md#scarcity) and has an agreed upon assigned value. Before [currency](helium-glossary.md#currency), people traded goods in exchange for [services](helium-glossary.md#service), known as bartering. There was a shortcoming in bartering; people without the goods a service provider needed were unable to receive that service. This gave way to currency, which hasn’t changed much since that time. Currency had scarcity, typically a coin or precious metal, and everyone agreed that it had value.

### [_**Cryptocurrency**_](helium-glossary.md#cryptocurrency)

What is [Digital Currency](helium-glossary.md#digital-currency)? Why do we agree to assign it value? How is it [scarce](helium-glossary.md#scarcity)? A digital currency designed to work as a medium of exchange through a computer [network](helium-glossary.md#network) which lacks a [centralized](helium-glossary.md#centralized) authority. Valuable due to [digital scarcity](helium-glossary.md#digital-scarcity). Becoming acquainted with the concepts below will provide a clearer understanding of [mining](helium-glossary.md#mining) a [cryptocurrency](helium-glossary.md#cryptocurrency).

### [_**Centralized**_](helium-glossary.md#centralized) ** **_**vs.**_** ** [_**Decentralized**_](helium-glossary.md#decentralized)

Centralized networks host a single server, and in the event this server is taken down, the network goes down with it. [Bitcoin](helium-glossary.md#bitcoin), for example, is a [decentralized](helium-glossary.md#decentralized) [peer to peer network](helium-glossary.md#peer-to-peer-network), where [miners](helium-glossary.md#miner) are awarded Bitcoin for [mining](helium-glossary.md#mining) new [blocks](helium-glossary.md#block), which in Bitcoin's instance is a [ledger](helium-glossary.md#ledger) of transactions made on the Bitcoin [blockchain](helium-glossary.md#blockchain). Decentralized networks like these are difficult for competitors or governments to take down because even if one or many [nodes](helium-glossary.md#nodes) are taken off-line, the network will continue to share [data](helium-glossary.md#data) over the remaining nodes, leaving the [software](helium-glossary.md#software) [service](helium-glossary.md#service) provided uninterrupted.

### _What is_ [_Blockchain_](helium-glossary.md#blockchain)_?_

A [blockchain](helium-glossary.md#blockchain) is a highly secure [software](helium-glossary.md#software) that functions as a [publicly distributed ledger](helium-glossary.md#distributed-ledger) to record transactions and house the software protocols a network uses to function. Consists of individual “[blocks](helium-glossary.md#block)” linked together using [cryptography](helium-glossary.md#cryptography), which each contain an [immutable](helium-glossary.md#immutable) encrypted record of all the blocks that precede it, known as a “[hash](helium-glossary.md#hash)”.

### _What is a_ [_Hash Function_](helium-glossary.md#hash-function)_?_

A fundamental tool in [cryptography](helium-glossary.md#cryptography), a [cryptographic hash function](helium-glossary.md#cryptographic-hash-function) is an algorithm that takes an arbitrary amount of data input and outputs a fixed-size output, from which it is computationally infeasible to determine the input.

_Fun fact: 2^80 computational steps is the computational bound for infeasibility._

### [_**Immutability**_](helium-glossary.md#immutable)

The inability to be altered after its creation, another key component of [blockchain](helium-glossary.md#blockchain) technology. This makes it impossible for any entity, for example, a government or corporation, to manipulate, replace, or falsify [data](helium-glossary.md#data) stored on the [network](helium-glossary.md#network), and reduces the time and cost of audits by simplifying the verification of information. Immutability increases overall efficiency of organizations by providing them with the opportunity to maintain historical record of their business processes, providing clarity to many business disputes by enabling a verifiable, shared source of truth.

### _What is a_ [_Consensus Mechanism_](helium-glossary.md#consensus-mechanism)_?_

[Helium](helium-glossary.md#helium) [hotspots](helium-glossary.md#hotspot) share [data](helium-glossary.md#data) with one another and [validators](helium-glossary.md#validator), who then report that data to the Helium network. In Helium’s instance, the data recorded is transactions made on the Helium network and a hash of all the previous blocks. Validators are larger computers used to verify the accuracy of [HNT](helium-glossary.md#hnt) transactions, [Proof of Coverage](helium-glossary.md#proof-of-coverage) information submitted by hotspots, and to submit [challenges](helium-glossary.md#challenge) on our hotspot’s behalf. Each new [block](helium-glossary.md#block) contains a [hash function](helium-glossary.md#hash-function), an encrypted copy, of all the previous blocks that came before it.

In the event a transaction is manipulated, (_for example, by attempting to “_[_double spend_](helium-glossary.md#double-spend)_” by changing a recipient’s_ [_wallet_](helium-glossary.md#crypto-wallet) _address etc_.), this will dramatically change the [hash function](helium-glossary.md#hash-function) of that [block](helium-glossary.md#block). Each block that follows this manipulated block will contain the incorrect hash function, and will not match the copy of the [blockchain](helium-glossary.md#blockchain) provided by other [nodes](helium-glossary.md#nodes). This [immutability](helium-glossary.md#immutable) ensures the data reported by the network to be current and accurate.

_“A node ‘votes’ for a block by adding it to its local copy of the_ [_blockchain_](helium-glossary.md#blockchain)_, and propagating that block to its immediate peers, who then add it to their copy of the blockchain and propagate it, and so on, until all nodes have the block in their local copy of the blockchain.”_

_This information and more available at_ [_Blockgeeks_](https://blockgeeks.com/)\_\_

### _What is_ [_DeFi_](helium-glossary.md#defi)_?_

[Decentralized](helium-glossary.md#decentralized) companies providing [software](helium-glossary.md#software) [services](helium-glossary.md#service) incentivize individuals to all behave the same way by [rewarding](helium-glossary.md#reward) them with a [native token](helium-glossary.md#native-token) for playing by the rules. These native tokens can be [exchanged](helium-glossary.md#exchange) for other [cryptocurrencies ](helium-glossary.md#cryptocurrency)or sold for [fiat](helium-glossary.md#fiat) [currencies](helium-glossary.md#currency). Under this model, folks who play by the rules are rewarded, but even given the instance everyone were to behave as selfishly as possible, and do what is best for their own interest, the system will still thrive.

_By making it more expensive to cheat the system than to play by the rules,_ [_miners_](helium-glossary.md#miner) _are encouraged to behave the same way and work on the same_ [_block_](helium-glossary.md#block)_. They’re playing against each other in a game that winning will provide a larger reward than cheating. This is what gives_ [_digital currency_](helium-glossary.md#digital-currency) \_\_ [_scarcity_](helium-glossary.md#scarcity)_, and therefore value._

### [_**Scarcity**_](helium-glossary.md#scarcity)

Coming full circle, back to the very concept that gives [money](helium-glossary.md#money) itself its value, [digital scarcity](helium-glossary.md#digital-scarcity) is what gives value to [cryptocurrency](helium-glossary.md#cryptocurrency). The "[Double-Spend](helium-glossary.md#double-spend-problem)" problem, which devalued early [digital](helium-glossary.md#digital-currency) [currencies](helium-glossary.md#currency), was solved by an anonymous developer, or group of developers using the moniker [Satoshi Nakamoto](helium-glossary.md#satoshi-nakamoto) by using [cryptography](helium-glossary.md#cryptography) and a publicly [distributed digital ledger](helium-glossary.md#digital-ledger) to create the [Bitcoin](helium-glossary.md#bitcoin) [blockchain](helium-glossary.md#blockchain). [Satoshi](helium-glossary.md#satoshi) used [game theory](helium-glossary.md#game-theory), which incentivizes decisions that are best for the [network](helium-glossary.md#network), and imposes disincentives that make cheating the network unaffordable, which encourages individuals with free will to perform a target action. This technology is the fundamental starting point of all modern [cryptocurrencies](helium-glossary.md#cryptocurrency) and creates [digital scarcity](helium-glossary.md#digital-scarcity) by making replicating the [currency](helium-glossary.md#currency) or falsifying data unfeasible.
