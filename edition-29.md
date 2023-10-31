---
description: 02/15/2023
---

# EDITION #29

![](<.gitbook/assets/DAO News (15x5) (1).jpg>)

### **👋 Hello!**

Hello and welcome to the Ethereum Name Service DAO Newsletter!

New editions are **published on the 1st and 15th of every month.**

This newsletter is available on the [ENS DAO Governance Forum](https://discuss.ens.domains/) and [Substack](https://ensdaonews.substack.com/).

We encourage any feedback, questions, or comments!

***

### 📰 Newsletter Updates

* Our entire archive is now available to view in its own section on the [**forum**](https://discuss.ens.domains/c/dao-wide/newsletter/72).
* Our homepage is hosted on IPFS at [**ensdaonews.eth.limo**](https://ensdaonews.eth.limo/) or [**ensnews.eth.limo**](https://ensnews.eth.limo/).
* We have a new [**Global**](https://ensdaonews.substack.com/s/submissions) section to feature multilingual articles.

\--

### **🗓 ENS Calendar**

_For the most up-to-date schedule of events, refer to the_ [**ENS Calendar**](https://ensnews.eth.limo/calendar.html).

* [**ENS DAO Q1/Q2 2023 Dashboard**](https://discuss.ens.domains/t/ens-dao-term-3-dashboard/15799)
* **Calendar:** [Public Access](https://calendar.google.com/calendar/embed?src=8im77u2b3euav0qjc067qb00ic%40group.calendar.google.com\&ctz=auto)
* **Calendar:** [Access with Gmail](https://calendar.google.com/calendar/u/1?cid=OGltNzd1MmIzZXVhdjBxamMwNjdxYjAwaWNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

\--

### 🗳️ [Recent Proposals](https://snapshot.org/#/ens.eth)

| Status | Proposal                                                | Discussion                                                                                     | Vote                                                                                                                           |
| ------ | ------------------------------------------------------- | ---------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Passed | \[EP3.3] \[Executable] Sell ETH into USDC               | [Link](https://discuss.ens.domains/t/draft-executable-sell-eth-into-usdc/15906/)               | [Tally](https://www.tally.xyz/gov/ens/proposal/45461903078948131870051132081249892009497709518413744958551889217805827301425)  |
| Passed | \[EP3.2] \[Executable] Q1/Q2 2023 Working Group Funding | [Link](https://discuss.ens.domains/t/ep-3-2-executable-q1-q2-2023-working-group-funding/16123) | [Tally](https://www.tally.xyz/gov/ens/proposal/105292919185331921858643224173178583901390266903267892669205105842869373522526) |

\--

**Upcoming Votes**:

| Proposal                                                  |                                                 Discussion                                                |
| --------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------: |
| \[Draft] \[Executable] Fund The Endowment (first tranche) | [Link](https://discuss.ens.domains/t/draft-executable-fund-the-endowment-first-tranche/16277?u=estmcmxci) |

_For details on the ENS DAO proposal process see our_ [**Governance Docs**](https://docs.ens.domains/v/governance/).

\--

### 🌐 Ecosystem Updates

#### Gitcoin Alpha Round: Funder Spotlight

The [Gitcoin Alpha Round](https://go.gitcoin.co/blog/announcing-the-gitcoin-alpha-round) concluded on January 31st. A [Twitter space](https://twitter.com/gitcoin/status/1623053612846059520) was held on February 8th, spotlighting the funders of the Alpha round's Open Source Software and Ethereum Infrastructure categories.

@Coltron.eth from the Public Goods Working Group (@PublicGoods\_Stewards) was present and joined the stage. The Public Goods and Ecosystem working group have a history of using Gitcoin for grant funding and are evaluating the Alpha round success.

**Takeaways**

* Gitcoin will provide Alpha round funders with more data on round outcomes so that they can better make funding decisions.
* Gitcoin is looking to improve the website's user interface for donors.
* Donors who contributed should verify [their Gitcoin passports](https://twitter.com/gitcoin/status/1625248307475005443) before midnight UTC Friday, February 17th. Only donors with verified passports will have their contributions eligible for matching.

Play the [recording now](https://twitter.com/i/spaces/1ypJddLbEkrJW).

\--

#### Postmortem: Null byte vulnerability in ENS subgraph

> "Recently we had a vulnerability in our subgraph that was previously patched reoccur. We've just released a postmortem describing why this happened, and how we'll prevent this kind of thing from happening again in the future." - @nick.eth

Read more about how the core team resolved this vulnerability [here](https://ens.mirror.xyz/9GN77d-MqGvRypm72FcwgxlUnPSuKWhG3rWxddHhRwM).

\--

#### ENS Data: JSON based Text Record Lookup

ENS Data looks up ENS text records for any address and returns them in JSON format. Simply append a wallet address or ENS after ensdata.net; records are cached for 48 hours. Support this project by sending ETH to _`ens.pug.eth`_

\--

#### ENS Domains at StarkWare 2023

@matoken.eth presented ENS at the Starknet sponsored StarkWare sessions.

> "StarkNet is one of the so-called "Layer 2" chains that depend on the network's security to Ethereum Layer 1 using the technology called "ZK Rollup." StarkWare is the development company behind the chain and I was honoured to be invited to their annual event, \[StarkWare Sessions]\(https://starkwaresessions.co/.. in Tel Aviv. In this blog post, I would like to cover the vibe of the event and how ENS fits into this new upcoming community." - matoken.eth

Read the full blog post [here](https://ens.mirror.xyz/Lznxnu4tBovdWcsv7QHFCieXaTddpdKKDrN4nfZSzxk).

\--

#### ETH Denver

ENS Labs and the Ecosystem Stewards are coordinating two events at ETH Denver. The first event will be hosted at the Cooper Lounge on March 2nd at 6pm local time. Stay tuned for more information on the second and possibly third event.

If you're going to be at ETH Denver, let the team know by filling out the [ETH Denver Roll Call for The ENS Community](https://app.deform.cc/form/e3248ac4-a860-486a-aa45-cd3f0515e421/). Be sure to join the [ETH Denver Telegram channel](https://t.me/+6hYE1c6i1wM1OTIx) as well.

\--

#### Gasless DNSSEC implementation

The first stage of the new resolver contracts are complete. This implementation makes it possible for anyone with a DNS name to ENS-enable it by setting DNS text records without charge. After implementing the custom resolver, it'll be possible to specify the contents of ENS records inside a DNS text record.

> "I’m pleased to announce that I’ve completed work on the first stage of the new resolver contracts for gasless DNSSEC integration. This will make it possible for anyone with a DNS name to ENS-enable it by setting DNS TXT records, with no onchain gas fees whatsoever." - @nick.eth

Read more on the [forum](https://discuss.ens.domains/t/update-on-gasless-dnssec-implementation/16305).

\--

#### Auth0 x ENS

ENS Labs partnered with The Auth0 Lab, who are developing verifiable credentials, a W3C standard for digitally cryptographically verifiable credentials. This partnership enables seamless ENS profile data look-ups to application developers.

Read more on how this works [here](https://auth0.com/blog/fetch-ens-profile-data-using-okta-customer-identity-cloud/).

\--

#### Beer.eth

We love beer.eth, too.

> beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth beer.eth
>
> — Budweiser (@budweiserusa) [February 9, 2023](https://twitter.com/budweiserusa/status/1623475248564785154?ref\_src=twsrc%5Etfw)

\--

#### Temp Checks

**Second Airdrop:** A temp check was posted on the forum about a second $ENS airdrop. The proposal asks the DAO to distribute the 5.4 million unclaimed ENS tokens from the first airdrop to the community, based on some of the similar requirements at the first. To be eligible for the distribution, users must have set an ENS record for their Ethereum address by a agreed upon date. Some other factors may come into play.

Read the discussion on the [forum](https://discuss.ens.domains/t/temp-check-ens-token-2nd-airdrop/16071).

\--

#### Community

Three ENS Twitter spaces were held in the first half of February.

* [\[EP3.2\] Working Group Funding (Feb 1st, 2023)](https://twitter.com/ENS\_DAO/status/1620742665783627777?s=20\&t=xr1XVkFAV1baR8f4PXOtbg)
* [Builders and Community Open Mic (Feb 2nd, 2023)](https://twitter.com/ensdomains/status/1621221938315116545?s=20\&t=\_8JGkS5dWbDOt\_8UUbaD9w)
* [Charity, ENS Widgets, Seaport (Feb 9th, 2023)](https://twitter.com/ensdomains/status/1623420487442305024?s=20\&t=\_8JGkS5dWbDOt\_8UUbaD9w)
* [Giga thread: how to participate in ENS DAO governance - @dr3a.eth](https://twitter.com/dr3a\_eth/status/1624103411628257281?s=20\&t=1XC6R8H9\_R8MXj5M3jKxWg)

\--

### 📰 Working Group News

For Q1/Q2 2023, the lead stewards for each working group are:

* Meta-Governance – @katherine.eth
* ENS Ecosystem – @slobo.eth
* Public Goods – @Coltron.eth

_The responsibilities of lead stewards are set out in Rule 8.7 of the_ [**Working Group Rules**](https://docs.ens.domains/v/governance/governance-proposals/term-1/ep12-working-group-rules).

\--

#### ENS DAO Working Group Schedule (Q1/Q2 2023):

| Working Group   | Time    | Day      | Location                                            |
| --------------- | ------- | -------- | --------------------------------------------------- |
| Meta-Governance | 7pm UTC | Tuesday  | [Google Meet](https://meet.google.com/ihz-hdvb-bbq) |
| Ecosystem       | 5pm UTC | Thursday | [Google Meet](https://meet.google.com/ecv-oizn-psi) |
| Public Goods    | 6pm UTC | Thursday | [Google Meet](https://meet.google.com/iko-moej-rxc) |

\--

#### ⚖️ [Meta-Governance](https://discuss.ens.domains/c/meta-governance/28)

**The Meta-Governance working group hosts its weekly meeting, Tuesday's at 7PM UTC.**

* [Minutes: Feb 7th, 2023](https://discuss.ens.domains/t/metagov-working-group-weekly-meeting-2pm-et-tuesday/15981/5?u=estmcmxci)
* [Minutes: Feb 14th, 2023](https://discuss.ens.domains/t/metagov-working-group-weekly-meeting-2pm-et-tuesday/15981/5?u=estmcmxci)

\--

**Endowment Updates:**

The Karpatkey team have posted [an FAQ](https://discuss.ens.domains/t/endowment-frequently-asked-questions-faq/16228) on the forum. They've also posted a first draft of the [Executable Proposal to fund the Endowment](https://discuss.ens.domains/t/draft-executable-fund-the-endowment-first-tranche/16277).

**Abstract**: First tranche to fund the Endowment with 16,000 ETH sent from ENS DAO (controller) to the ENS Endowment and an additional 150 ETH sent to the Meta-Gov Pod to account for Karpatkey and Steakhouse monthly fees.

> We have posted an executable proposal draft to forum. There is also an Endowment FAQ 2 posted to the forum. We are waiting for the community to align/provide feedback, and we will take it to an on-chain vote. We made changes to the proposal based on feedback we have received. We are hoping to take it to an on-chain vote shortly. We are ready to move forward! Prior to on-chain voting, we need to transfer ownership to the ENS DAO. This can be done easily with one transaction.
>
> \-- @santinomics.eth

\--

**Updates on \[EP 3.3] Sell 10k ETH to USDC:**

The ENS DAO successfully swapped 10k ETH for $16,226,542 USDC via CoW Swap.

![](upload://zwF0uijsib4cOmf3AdknubfAvb6.jpeg)

Check the transaction here: [Etherscan](http://etherscan.io/tx/0xa2ba7939818d920aef9d1b2e1222d4df962ac30610367c0ec67c3a0fb3c5dbbc), [CoW Explorer](https://explorer.cow.fi/orders/0xff2e2e54d178997f173266817c1e9ed6fee1a1aae4b43971c53b543cffcc2969845c6f5599fbb25dbdd1b9b013daf85c03f3c63763e4bc4a)

\--

#### 🔄[ENS Ecosystem](https://discuss.ens.domains/c/ens-ecosystem/32)

**The ENS Ecosystem working group hosts its weekly meeting, Thursday's at 5PM UTC.**

* [Minutes: Feb 2nd, 2023](https://discuss.ens.domains/t/ens-ecosystem-working-group-weekly-meeting-12pm-et-thursday/15985/6?u=estmcmxci)
* [Minutes: Feb 9th, 2023](https://discuss.ens.domains/t/ens-ecosystem-working-group-weekly-meeting-12pm-et-thursday/15985/8?u=estmcmxci)

\--

**Project Highlights:**

1. [Next Generation ENS Front-End and NameWrapper - leontalbert.eth & domico.eth](https://alpha.ens.domains): Leon and Dom of ENS Labs gave the community a walkthrough of the new and improved frontend for the Name Wrapper on Goerli testnet. The goal of the Name Wrapper is to make it easier to understand for new users, while retaining information for experienced ones. The V3 ENS App preview is on testnet at alpha.ens.domains.
2. [ENS Registration Widget - gregskril.eth](https://discuss.ens.domains/t/ens-registration-widget/16222): A widget that allows any react website to implement and register ENS names in a few flexible ways. It also allows tracking of who registered a name using your widget via Platform Source Parameter for Registrar Controller. It has options for styling and customization. The widget is open source and available on Github.
3. [ENS Doc - julieshi.eth](https://twitter.com/julieshi\_eth/status/1620517453481803780?s=20\&t=1XC6R8H9\_R8MXj5M3jKxWg): [ENS Doc](https://ens-doc.vercel.app/sh36MOVrmE) allows you to upload and share your file in a safe way. To use it, choose a file to upload and enter the ENS address you would like to share the file with. The site creates a randomized file link to download the file that only the specified address will have access to. It uploads the file to IPFS and a backend stores the hash of the file location. The backend checks if the requesting address has permission to download the file. We still need to fix the issue of being able to guess the location of the file on IPFS without permission.
4. [ENS Messaging Provider (MP) record for web3 messaging - galligan.eth](https://discuss.ens.domains/t/ens-messaging-provider-mp-record-for-web3-messaging/14520): The project proposes to use [XMTP (Extensible Message Transport Protocol)](https://xmtp.org/) to build a protocol for secure messaging in Web3, utilizing ENS to send messages between accounts, including DMs, alerts, announcements, and more. Original post: [September 2022](https://discuss.ens.domains/t/ens-messaging-provider-mp-record-for-web3-messaging/14520)

\--

**Upcoming Events:**

1. Matoken.eth will be presenting at ETHPorto, hosted in Lisbon from March 16th to the 18th. He'll be relaying his insights on "ENS for the multi-chain world". Tickets available: ethporto.ticketeth.xyz
2. ETHDenver Roll Call for the ENS community - [link here](https://app.deform.cc/form/e3248ac4-a860-486a-aa45-cd3f0515e421/)

\--

#### ✅ [Public Goods](https://discuss.ens.domains/c/public-goods/37)

**The Public Goods working group hosts its weekly meeting, Thursday's at 6PM UTC.**

* [Minutes: Feb 2nd, 2023](https://discuss.ens.domains/t/public-goods-working-group-weekly-meeting-1pm-et-thursday/15982/3?u=estmcmxci)
* [Minutes: Feb 9th, 2023](https://discuss.ens.domains/t/public-goods-working-group-weekly-meeting-1pm-et-thursday/15982/4?u=estmcmxci)

\--

**Project Highlights:**

1. [Pairwise - griff.eth](https://pairwise.generalmagic.io/): Pairwise lets you set up a space with a pairwise comparison for voting. (A vs B presentation). No on-chain transactions required, similar to Snapshot. Currently in beta, and development is paused, pending additional funding. The long term goal of Pairwise is to make voting “disappear,” and make it become a seamless way to signal preference.
2. [DoDAO - Robin](https://dodao.academy/courses): DoDAO is an education platform that divides content into guides, with reinforced learning and questionnaires. They are on a mission to onboard one million people to DeFi, DAOs and NFTs by 2025.
3. [Inverter Network - Mert](https://twitter.com/inverternetwork): The goal of Inverter Network is to interconnect the novel technologies of web3 to the grounded funding infrastructures of traditional organizations by improving access to funding and inspiring distributed ownership for builders and funders.

\--

**Upcoming Events:**

1. Schelling Point -- The Public Goods working group will be sponsoring Schelling Point during ETH Denver on March 2nd. Schelling Point is a whole day dedicated towards public goods talks.

\--

### ⚙️ Integrations

1. [SIWE and Shopify](https://twitter.com/signinwitheth/status/1623805256973819904?s=20\&t=1XC6R8H9\_R8MXj5M3jKxWg) Sign-In with Ethereum (SIWE), a new, Ethereum-native form of authentication, which enables users to control their digital identity with their Ethereum address and ENS profile, recently announced their integration with e-commerce giant, Shopify. This integration demonstrates a key feature of ENS, reverse resolution, which allows for the user to be represented on a dApp by their ENS primary name, instead of their long hash address.
2. [Reverse and avatar resolution with DeForm](https://twitter.com/thatguyintech/status/1623771307048587266?s=20\&t=1XC6R8H9\_R8MXj5M3jKxWg) DeForm features forms and surveys for token-enabled communities. The app is being used by ENS Labs and the Ecosystem Working Group to manage sign-ups for the ENS community event at ETH Denver. Primary name and avatar resolution are now functional on the app as well.

\--

### 🔒 Security Tip

**🚨 ALERT**

As reported by Web3 security agency [PeckShield](https://twitter.com/PeckShieldAlert/status/1611189561308372993), fake $ENS airdrop scams continue. This example shows that even accounts marked as "Verified" are often compromised and used to deploy a lookalike page that appears almost exactly like the real one.

These types of lookalike accounts do everything possible to appear like the legitimate account in hopes of tricking unsuspecting victims into giving up their private information, such as their crypto wallet's _seed phrase._

**The only $ENS airdrop claim closed on May 4th, 2022. Any site claiming they will give you $ENS is fake. Don't attempt to "claim" these offers, or even connect your wallet to these sites.**

Review this helpful thread by ENS Labs for more on how to safeguard your assets:

> 🚨 There's been an uptick in new phishing sites that target the ENS community. Remember, your .eth name is an ERC-721 NFT. Any malicious contract or website that targets NFTs can possibly transfer ownership of your ENS name!\
> \
> ⚔️ Here are a few tips to protect yourself ⚔️ ⬇️
>
> — ens.eth (@ensdomains) [February 2, 2023](https://twitter.com/ensdomains/status/1620936457878933507?ref\_src=twsrc%5Etfw)

\--

**⚠️ REMEMBER**

* _**NEVER give your private seed phrase to anyone, or enter it into any website, for any reason.**_ Your seed phrase has the same function as your password, and with it an attacker is granted complete access to your crypto assets.
* **There is no second airdrop!** Anything that says there is - even in what appears to be from a legitimate source - is **lying to you,** and wants to steal your crypto!

\--

### 🤝 Get Involved

* Follow the [ENS DAO](https://twitter.com/ENS\_DAO) and [ENS DAO Newsletter](https://twitter.com/ensdaonews) accounts on Twitter.
* Join our [Governance Forum](https://discuss.ens.domains/).
* [Join on our Discord](https://chat.ens.domains) to chat about ENS or speak to a moderator.
* Visit our [Governance Docs](https://docs.ens.domains/v/governance/).
* View our [Support Docs](https://support.ens.domains/docs) for answers to common questions about ENS.
* Remember to delegate $ENS on [ENS Agora](https://agora.ensdao.org/) to participate in voting.

***

Thank you very much for reading! Take care. :wave:
