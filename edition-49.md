---
description: 12/5/2023
---

# EDITION #49

<figure><img src=".gitbook/assets/DAO News (15x5) (1).jpg" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**⚠️ NOTICE:**

We value the voice of our community and are always eager to hear from you. The ENS team actively encourages feedback on all updates to better our system and enhance user experience. Please share your thoughts, suggestions, or concerns at **ens.canny.io**.
{% endhint %}

\_

### ☀️ Welcome!

_Welcome to the ENS DAO Newsletter:_

* [🗓️ **New editions**](https://paragraph.xyz/@ensdao) — published bi-weekly (Tuesday)
* [📑 **Previous editions**](https://discuss.ens.domains/c/dao-wide/newsletter/72) are archived on the [**ENS DAO Archive**](https://ens-dao-newsletter.gitbook.io/archive/).
* [🗳️ **New proposals**](https://t.me/ensdao\_notifications) are broadcasted to Telegram.
* [💬 **Submit feedback**](https://newsletter.deform.cc/) — tell us what to feature!

—

### 📰 Newsletter Roundup (tl;dr)

* **ENS Labs Update**: ENS November Stats, Patent Debate, Repo Updates
* **Community Updates**: teamnick.xyz, 1W3 Browser Extension, cb.id subnames Milestone
* **Meta-Governance**: November Financial Report, Guidelines for Service Providers
* **Public Goods:** Project Presentations
* **Ecosystem:** ENS.js v3 Update, EVM Gateway on Arbitrum

—

### **🗓 Calendar**

Refer to [**ENS DAO Calendar**](https://calendar.google.com/calendar/u/0/embed?src=8im77u2b3euav0qjc067qb00ic@group.calendar.google.com\&ctz=auto) for ENS DAO working group calls and other events.

* **Calendar:** [Public Access](https://calendar.google.com/calendar/embed?src=8im77u2b3euav0qjc067qb00ic%40group.calendar.google.com\&ctz=auto)
* **Calendar:** [Access with Gmail](https://calendar.google.com/calendar/u/1?cid=OGltNzd1MmIzZXVhdjBxamMwNjdxYjAwaWNAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)

—

### 🗳️ [Recent Proposals](https://snapshot.org/#/ens.eth)

| Proposal                                             |                                                Discussion                                               |   Vote  |
| ---------------------------------------------------- | :-----------------------------------------------------------------------------------------------------: | :-----: |
| \[EP4.9]\[Social] Select providers for EP4.7 streams | [Open](https://discuss.ens.domains/t/ep4-9-social-select-providers-for-ep4-7-streams/18309?u=estmcmxci) | Pending |

#### Steward Elections and Service Provider Vote

The DAO will be conducting Steward Elections concurrently with the Service Provider vote. We ask delegates to review proposals carefully before casting their vote. For more information on the [Steward Election Process](https://discuss.ens.domains/t/call-for-nominations-for-term-5-steward-elections-calendar-2024/18296) and the [Service Provider vote](https://discuss.ens.domains/t/update-on-the-ens-streams-dates-rules-and-implementation/18138/30), click either respective hyperlink.

**Voting Itinerary**

* December 6-9: Nomination Period for Steward Elections
* December 10: Steward Elections begin at 9am UTC
* December 15: Steward Elections end at 9am UTC

**Nomination Statements:**

* [Service Provider Nomination Thread](https://discuss.ens.domains/t/service-provider-stream-nomination-thread/18142?u=estmcmxci) and [PDF](https://smallpdf.com/result#r=f741cc2756d4e70ec379587dd94d11af\&t=share-document)
* [Meta-Governanance Nomination Thread](https://discuss.ens.domains/t/steward-nominations-ens-metagovernance-working-group-term-5-calendar-2024/18293?u=estmcmxci)
* [Ecosystem Nomination Thread](https://discuss.ens.domains/t/steward-nominations-ens-ecosystem-working-group-term-5-calendar-2024/18294?u=estmcmxci)
* [Public Goods Nomination Thread](https://discuss.ens.domains/t/steward-nominations-ens-public-goods-working-group-term-5-calendar-2024/18295?u=estmcmxci)

—

_Note: A minimum of 100k $ENS is required to submit executable proposals. Once a proposal gains momentum, the stewards will prioritize it for a vote during the designated voting window. See our_ [_**Governance Docs**_](https://docs.ens.domains/v/governance/) _for more information. To view the real-time distribution of voting power among delegates, visit_ [_votingpower.xyz_](https://votingpower.xyz)_._

—

### 🌀 ENS Labs Updates

#### 📈 ENS Stats: November 2023

In [November 2023](https://x.com/ensdomains/status/1731723539965985152?s=20), ENS (Ethereum Name Service) saw substantial activity with 20.8k new .eth domain registrations, increasing the total number of names to 2.3 million. This activity generated $1.1 million in protocol revenue, which was entirely directed to the ENS DAO. The ENS ecosystem expanded with 16k new Ethereum accounts holding at least one ENS name, bringing the total to 795k accounts. The month also marked the setting of 14k primary ENS names, resulting in a total of 690k names. In addition to these milestones, the personalization of ENS profiles grew with 3.5k new avatar records set, achieving a total of 138k avatars.

—

#### 🛠️ Recent updates from the [ENS Repository](https://github.com/ensdomains)

> _Notice: Please be informed that the ENS Repository has been updated with new commits and actions in the past two weeks since our last newsletter. While we strive for accuracy, there may be instances of incompleteness or errors. For the most precise and up-to-date information, we recommend checking the_ [_ENS Repository_](https://github.com/ensdomains) _directly. We appreciate your understanding and encourage your due diligence._

1. **Repository: ensdomains/offchain-gateway-rs**
   * Antony1060 (Merged PR): [`Implement encoding for multicoins`](https://github.com/ensdomains/offchain-gateway-rs/pull/1)
   * Antony1060 (Commit): [`Basic multicoin address encoding (working ETH)`](https://github.com/ensdomains/offchain-gateway-rs/commit/8d9cdde)
   * Antony1060 (Commit): [`Fix comment`](https://github.com/ensdomains/offchain-gateway-rs/commit/02d4363)
   * Antony1060 (Commit): [`Implement multicoin encoding`](https://github.com/ensdomains/offchain-gateway-rs/commit/67420c6)
   * Antony1060 (Commit): [`Misc`](https://github.com/ensdomains/offchain-gateway-rs/commit/3969035)
   * lucemans (Merged and Deleted Branch): [`feat/multicoin-encoding`](https://github.com/ensdomains/offchain-gateway-rs/pull/1)
2. **Repository: ensdomains/offchain-resolver**
   * mdtanrikulu (Merged PR): [`retrieve signer from extradata for proxy calls`](https://github.com/ensdomains/offchain-resolver/pull/38)
   * mdtanrikulu (Commit): [`retrieve signer from extradata for proxy calls`](https://github.com/ensdomains/offchain-resolver/commit/0db7904)
   * mdtanrikulu (Commit): [`update test`](https://github.com/ensdomains/offchain-resolver/commit/aec03fc)
   * mdtanrikulu (Merged and Deleted Branch): [`mdt/retrieve-signer-from-extradata`](https://github.com/ensdomains/offchain-resolver/pull/38)
3. **Repository: ensdomains/governance-docs**
   * ENSpunks (Update): [`Update README.md`](https://github.com/ensdomains/governance-docs/commit/4af6c1c)
   * Arachnid (Merge Pull Request): [`Merge pull request #50 from ENSpunks/patch-1`](https://github.com/ensdomains/governance-docs/commit/4af6c1c)
4. **Repository: ensdomains/ens-metadata-service**
   * mdtanrikulu (Open PR): [`migrate ethers v6, add sepolia support`](https://github.com/ensdomains/ens-metadata-service/pull/168)
   * mdtanrikulu (Comment): [`Note: tests will succeed when ens-avatar ethers v6 migration is ready and published`](https://github.com/ensdomains/ens-metadata-service/pull/168)
   * mdtanrikulu (Changed Base Branch): [`Changed the base branch from master to mdt/os-api-config`](https://github.com/ensdomains/ens-metadata-service/pull/168)
5. **Repository: ensdomains/ethers-ccip-read**
   * Antony1060 (Action): [Introduce a way for callers to get CCIP requests](https://github.com/ensdomains/ethers-ccip-read/pull/7)
6. **Repository: ensdomains/ens-avatar**
   * mdtanrikulu (Commit): [`improve url origin verification`](https://github.com/ensdomains/ens-avatar/commit/20ee5bc)
   * mdtanrikulu (PR): [`migrate ethers to v6 size #97`](https://github.com/ensdomains/ens-avatar/actions)
   * mdtanrikulu (Commit): [`increase the package size limit due to v6 changes CI #174`](https://github.com/ensdomains/ens-avatar/actions)
   * mdtanrikulu (Commit): [`improve url origin verification Deploy ESBuild site to Pages #10`](https://github.com/ensdomains/ens-avatar/actions)
7. **Repository: ensdomains/governance-web-react**
   * lucemans (Commit): [`Patch Sidenav Links`](https://github.com/ensdomains/docs-v2/commit/bf7936fd39bbcbc63c5fed6a3856bbf4467444c7)
   * lucemans (Commit): [`Update Naviation & Resolver Content`](https://github.com/ensdomains/docs-v2/commit/ca679494de2c0cc109eaea9f3545aee0d0f140ff)
   * lucemans (Commit): [`Patch Emoji in Navigation`](https://github.com/ensdomains/docs-v2/commit/5a089b7be1962021b2844e1d1bd52ad06049ae05)
   * lucemans (Commit): [`Introduce TLDs Page, Update Styling, and Rework Navigation`](https://github.com/ensdomains/docs-v2/commit/d64a5e6e8cd586047bf7cd786f6ff0936ab5b46b)
   * lucemans (Commit): [`Patch Content`](https://github.com/ensdomains/docs-v2/commit/e87254648bc280bde6f7254e89661df03525ad78)
   * lucemans (Commit): [`Patch Cleanup`](https://github.com/ensdomains/docs-v2/commit/b0e761c2a5b8b108068ac7a62c9f617093e410a5)
8. **Repository: ensdomains/governance-contracts**
   * mdtanrikulu (PR): [`onchain metadata support for multi deleagte`](https://github.com/ensdomains/governance-contracts/pull/25)
   * mdtanrikulu (PR): [`ens audit findings`](https://github.com/ensdomains/governance-contracts/pull/24)
9. **Repository: ensdomains/ensjs-v3**:
   * storywithoutend (Release): [v3.0.0-beta.11](https://github.com/ensdomains/ensjs-v3/releases/tag/v3.0.0-beta.11)
10. **Repository: ensdomains/evmgateway**
    * makoto (Commit): [`Added instruction on how to register names`](https://github.com/ensdomains/evmgateway/commit/ba0202ebbff3849bc0c4f527b6483027871275ee)
    * makoto (Commit): [`Crosschain resolver with reverse registrar`](https://github.com/ensdomains/evmgateway/commit/c52f671ad01aae9aaacb1df94fc90d0f72160574)
    * makoto (Commit): [`Add support interface`](https://github.com/ensdomains/evmgateway/commit/1b8c234c776ebb70c5c7b28d37ea17dcf118b542)
    * makoto (Commit): [`Add support interface to reverse registrar`](https://github.com/ensdomains/evmgateway/commit/4fb19071c3be446a46b8d80058b83a8363ca848d)
    * makoto (Commit): [`Change test name`](https://github.com/ensdomains/evmgateway/commit/2bd055c3ee60ad379868ec242c45f8dec667b17e)
    * makoto (Commit): [`Update L1 deployment contract address`](https://github.com/ensdomains/evmgateway/commit/ac19f164913cf17324bbbf9f46c4b10bbafb2580)
    * makoto (Commit): [`Remove offset from getTarget`](https://github.com/ensdomains/evmgateway/commit/7fb012844a7418b0d37f00860f05ec8e8faf5cb1)
    * makoto (Commit): [`Inherit Interfaces`](https://github.com/ensdomains/evmgateway/commit/f7fe6cda4dbc9b8a84afff0ae46713dc0c16991e)
    * makoto (Commit): [`Inherit interfaces for ReverseResolver`](https://github.com/ensdomains/evmgateway/commit/25065345ca724758e95f0fd08d04d1626e65bbe3)
    * makoto (Commit): [`Add ERC165 Signature`](https://github.com/ensdomains/evmgateway/commit/428fd9fb83cd4e4078226c7109f907d58e432f15)
    * makoto (Commit): [`Add support interface (#21)`](https://github.com/ensdomains/evmgateway/commit/9be51920aed43d96835e644ef60d24d05de86388)
    * makoto (Commit): [`Add goerli deployment info`](https://github.com/ensdomains/evmgateway/commit/ae749021c1079f506b2c04d92ebe054c208ea10e)
    * makoto (Commit): [`Change worker name`](https://github.com/ensdomains/evmgateway/commit/77a6b7c076b8992b3a807dcc732174b681a98c92)
    * makoto (Commit): [`Add comma`](https://github.com/ensdomains/evmgateway/commit/2c61006e308b492a28e4663d0ae3deae598f2426)
    * makoto (Commit): [`Change to single quote`](https://github.com/ensdomains/evmgateway/commit/479c4f85613ed0da0ed62455ad54783d5abbda9f)
    * makoto (Commit): [`Single quote`](https://github.com/ensdomains/evmgateway/commit/d4a53e22309b22b976d1997a3092905f8092eeb6)
    * makoto (Commit): [`Update README.md`](https://github.com/ensdomains/evmgateway/commit/381345af3f169162148aa60439ae6ff44f717144)
    * makoto (Commit): [`Update ccip-read-cf-worker to v0.0.3`](https://github.com/ensdomains/evmgateway/commit/3d98ec7d245202f974d4ba5efdf06307d852993b)
11. **Repository: ensdomains/ens-contracts**
    * TateB (PR): [`universal resolver safe calls + success var return`](https://github.com/ensdomains/ens-contracts/pull/292)
    * lcfr-eth (PR): [`add check in makeCommitment..`](https://github.com/ensdomains/ens-contracts/pull/293)
    * lcfr-eth (PR): [`Minor QA things`](https://github.com/ensdomains/ens-contracts/pull/294)
    * lcfr-eth (Commit): [`Update IETHRegistrarController.sol`](https://github.com/ensdomains/ens-contracts/commit/4654f35f205933a79690c29d067f11dfcf2ae762)
    * Arachnid (Commit): [`Merge pull request #294 from lcfr-eth/staging`](https://github.com/ensdomains/ens-contracts/commit/5ae0cd7500215fa0c6c8baa7491a4bda1b1634dd)
12. **Repository: ensdomains/ens-app-v3**
    * storywithoutend (Commit): [`Rever "update phantom logos"`](https://github.com/ensdomains/ens-app-v3/commit/6e4607e64489fbf54f5e85d19fd4cbd5de6baeae)
    * storywithoutend (Commit): [`Update moonpay.spec`](https://github.com/ensdomains/ens-app-v3/commit/8455b8f265ad47e2cdc43a47fd2e891133ad2fa9)
    * storywithoutend (Commit): [`Merge pull request #580 from ensdomains phantom-wallet`](https://github.com/ensdomains/ens-app-v3/commit/e1e0572ed0a3ea40e4c554f33a4b12236669792c)
13. **Repository: ensdomains/fix-mockup**
    * domicoeth (Commit): [`Use realistic values for registration mockup`](https://github.com/ensdomains/ensdomains-landing-v2/commit/ea379a2645855bd77b3cd0bc3aa79da798f1dde2)
    * TateB (Commit): [`Merge pull request #592 from ensdomains/fix-mockup`](https://github.com/ensdomains/ensdomains-landing-v2/commit/a5be85c87f28f237a00d5ff351c1d797ac351424)

—

#### Nick.eth Discusses Ongoing Patent Dispute

Nick.eth recently [spoke to CoinDesk](https://www.coindesk.com/tech/2023/11/21/we-are-prepared-to-go-to-the-mat-ens-founder-on-patent-dispute-with-unstoppable/) regarding a patent issue, claiming that Unstoppable Domains patented technology based on innovations developed by ENS. He is now considering challenging the patent, asserting the importance of open-source standards over patented technology. Unstoppable Domains, however, denies the validity of this claim, stating that their patent is for technology they independently developed and used, including unique features like gasless transactions. — — 11.21.23

—

#### Sadaf.eth Posits a Shift in Digital Identity Management

In a recent [thread](https://x.com/sadaf\_eth/status/1730693338477572385?s=20), Sadaf.eth, Director of Marketing for ENS Labs, posited that ENS represents a fundamental paradigm shift in digital identity management. The discourse emphasizes ENS's key principles of decentralization, trustlessness, permissionlessness, and interoperability, lauding the framework's innovative approach to blockchain technology. Sadaf.eth asserts that ENS extends beyond mere technical features; it is a commitment to democratizing the internet and promoting digital autonomy. The trustless and permissionless nature of ENS is portrayed as a stride towards inclusivity and a new standard in establishing digital trust, while its interoperability signifies a transformative step in facilitating seamless interactions across various blockchain platforms.

—

#### 📻 ENS Media Alerts

* [ENS Radio: Airstack](https://x.com/ensdomains/status/1729561836498903204?s=20) — 11.28.23
* [Community Space: Ethereum Follow Protocol](https://x.com/dr3a\_eth/status/1730400776080486826?s=20) — 11.30.23

—

### 🌐 Community Updates

#### Mint a Free Subname to Signal your Support for Open Innovation

In response to the ongoing public discussion about disputed patents, @slobo.eth has launched a site where the community can mint a complimentary `teamnick.eth` subname to signal their support for open-source and open standards in decentralized innovation. The site was built using technology such as [CCIP-read](https://eips.ethereum.org/EIPS/eip-3668), [ENSIP-10: Wildcard Resolution](https://docs.ens.domains/ens-improvement-proposals/ensip-10-wildcard-resolution) and more. This effort demonstrates a commitment to open innovation on the decentralized net. We encourage the community to mint their subname at teamnick.xyz — 11.27.23\
—

#### Onthis.xyz Introduces Shortcut Points

OnThis.xyz aims to improve the user experience by simplifying complex DeFi interactions. Instead of multiple steps to transact, ENS Shortcuts allow users to execute actions such as swaps, staking, or bridging with just a single domain reference, like sending ETH to specific ENS names like `portal.base.eth`. They are introducing an incentive layer for Shortcut creators and users where they can be rewarded for everyday transactions. To participate, users are instructed to create a post on the [Onthis Forum](https://forum.onthis.xyz) that describes their Shortcut and share it to boost activity and awareness. The Onthis team will select the Shortcut that receives the most support on the forum, then build and deploy it, including the creator's wallet address upon deployment. Users can then use a Shortcut to earn points. For more information, review their [thread on X](https://x.com/onthisxyz/status/1727078920594338125?s=20) — 11.21.23

—

#### Coinbase Wallet hits a Milestone, Surpasses 4 Million ENS Subnames

Coinbase Wallet has achieved a [significant milestone](https://twitter.com/sadaf\_eth/status/1729922945198518756?s=20) by issuing over 4 million ENS subnames to date via their cb.id domain. This achievement underscores the growing adoption of the Web3 ecosystem, with leaders like Sadaf.eth prompting users to secure their own ENS names if they haven't already. — 11.29.23

—

#### 1W3 Launches Browser Extension

ENS Ecosystem project [1W3](https://twitter.com/1W3io), a no-code web3 site builder, launched a browser extension which allows for ENS Website Resolver accessible on Chrome and Edge via extension. Check out their video tutorial and download the extension [here](https://chrome.google.com/webstore/detail/1w3-ens-website-resolver/mjjndfhdgdafdonmmpbmddiginkbclmi) to get started. — 11.28.23

—

#### ENS Vision Launches Forge

[Forge](https://forge.ens.vision) is an initiative by ENS.Vision at the forefront of developing open-source software dedicated to enhancing and innovating within the ENS Ecosystem. Their key offerings include:

* Forge.Node: This component efficiently consolidates ENS data from on-chain, off-chain, and secondary markets into one accessible location.
* Forge.Substore: A smart contract that enables users to create their own subdomain stores, facilitating the easy minting of subdomains from a parent domain. This is particularly useful for launching Initial Subdomain Offerings (ISOs).
* Forge.Registrar: This smart contract within Forge aids in domain registration by allowing the minting of multiple domains in a single transaction. Its design is gas-efficient and includes a built-in revenue-sharing program, making it an ideal choice for platforms that aim for streamlined domain acquisition and distribution.

Their team is committed to ongoing innovation and expansion, continuously evolving alongside the ENS ecosystem. — 11.29.23

—

#### Receipts XYZ Launches ENS-Supported Leaderboard

Receipts.xyz is a platform that integrates fitness achievements from Starva with blockchain technology. Users can connect their wallets, authenticate their fitness account achievements, and compete to be the top runner on their ENS-supported leaderboard. The platform then allows users to attest these accomplishments to their wallets using the Ethereum Attestation Service. This attestation process involves creating a metadata record of the achievement, which is then published to IPFS and can be queried by anyone. Additionally, users have the option to mint these attestations as NFTs, making them shareable and viewable across various applications and platforms. Essentially, Receipts.xyz provides a way to record and showcase fitness accomplishments using blockchain technology. — 12.1.23

—

#### ZKP2P Integrates ENS for Secure and Selective P2P Crypto Transactions

[ZKP2P](https://zkp2p.xyz) is creating a trustless P2P fiat-to-crypto onramp using zero-knowledge proofs (zk proofs) to ensure secure and private transactions. Its latest feature enables users to conduct transactions with selected counterparties, including those with ENS profiles. This capability not only enhances trust by allowing transactions with known entities but also leverages ENS for greater transparency in the P2P crypto space. — 12.1.23

—

#### Blockscout Enhances Data Reliability with Token Name Service Integration

The Token Name Service (TNS), which is built on ENS Protocol, has recently marked a significant milestone by [integrating with Blockscout](https://x.com/ensdomains/status/1730668698284028335?s=20), a blockchain explorer. TNS is a decentralized registry that assigns symbols to tokens and maintains a shared dataset of token metadata on the Ethereum Mainnet. With this integration, Blockscout can source accurate and decentralized token information directly from TNS, enhancing the information's reliability. This facilitates the provision of a decentralized source of truth for token metadata, such as names, logos, and project URLs, which is particularly valuable for tokens not listed on centralized platforms like Coingecko or CoinMarketCap. — 12.1.23

—

#### Interface Introduces ENS-Supported Suggested User List

Interface, a social platform for the Ethereum community, has introduced a "suggested user list" feature that promotes ENS names as the primary identifiers for its users. This innovative integration underscores the platform's commitment to leveraging Ethereum's unique capabilities to enhance the social connectivity within the blockchain space. By using ENS names, Interface not only simplifies user interactions but also fosters a sense of community and identity tied to the Ethereum ecosystem. This move aligns with the growing trend of integrating blockchain technology into social platforms to ensure user-centric, secure, and decentralized digital identities. — 12.1.23

—

#### Ethereum Follow Protocol (EFP) Announces Launch Partners

The Ethereum Follow Protocol (EFP) is poised to enhance ENS by adding a social graph component, with a planned rollout in the first half of Q1 2024. EFP aims to give ENS a competitive edge against rival social graph projects that offer their own naming and profiling systems. Key team members include brantly.eth, cory.eth, an innovator in the ENS ecosystem, and esm.eth, a developer known for his decentralized social media platform built on ENS and recognition in the Web3 space. These individuals bring a wealth of experience and deep connections within the ENS community, indicating a promising start for EFP. [Launch partners](https://x.com/BrantlyMillegan/status/1730701598811115934?s=20) include Skiff, Nifty Island, ENS Vision, Llamafolio, Interface, and more. — 12.1.23

—

### 📌 Working Group Bulletin

#### Q3/Q4 Lead Working Group Stewards + Secretary Appointment

**Appointments:**

* Meta-Governance – @katherine.eth
* ENS Ecosystem – @slobo.eth
* Public Goods – @Coltron.eth
* DAO Secretary - @limes

_The responsibilities of the Lead Stewards & Secretary are set out in Rule 9.8 and Rule 9.9 of the_ [_Working Group Rules_](https://docs.ens.domains/v/governance/governance-proposals/term-1/ep12-working-group-rules)_._

—

#### ENS DAO Working Group Schedule (Q3/Q4 2023):

| Working Group                                                                                                            | Time    | Schedule | Location                                            |
| ------------------------------------------------------------------------------------------------------------------------ | ------- | -------- | --------------------------------------------------- |
| ⚖️ [Meta-Governance](https://discuss.ens.domains/t/q3-q4-2023-budget-ens-metagovernance-working-group/17549?u=estmcmxci) | 3pm UTC | Tuesday  | [Google Meet](https://meet.google.com/ihz-hdvb-bbq) |
| 🔆 [Public Goods](https://discuss.ens.domains/t/q3-q4-2023-budget-ens-public-goods-working-group/17547)                  | 4pm UTC | Tuesday  | [Google Meet](https://meet.google.com/iko-moej-rxc) |
| 🌱 [Ecosystem](https://discuss.ens.domains/t/q3-q4-2023-budget-ens-ecosystem-working-group/17536?u=estmcmxci)            | 5pm UTC | Thursday | [Google Meet](https://meet.google.com/ecv-oizn-psi) |

_Note: The DAO will observe a moratorium in advance of the holiday season. This year's final Working Group meeting will take place on the 15th. The DAO will resume business as usual on the first fiscal business day of the new year (2024)._

—

### 🔨 [Meta-Governance](https://discuss.ens.domains/c/meta-governance/28)

**The Meta-Governance working group hosted its weekly meetings on November 21st, 2023 and November 28th, 2023:**

* [Minutes for Weekly Meta-Gov Meeting — November 21st](https://discuss.ens.domains/t/metagov-working-group-weekly-meeting-11am-et-tuesday/15981/51?u=estmcmxci)
* [Minutes for Weekly Meta-Gov Meeting — November 28th](https://discuss.ens.domains/t/metagov-working-group-weekly-meeting-11am-et-tuesday/15981/52?u=estmcmxci)

—

#### November 2023 Financial Report

The November 2023 financial report for ENS presents a positive financial outlook. Key highlights include:

1. **Sustainability:** The organization's revenues exceed its cash burn, with a cash inflow greater than the cash burn, ensuring a substantial runway of 134 months.
2. **Endowment:** The second tranche of the endowment has been funded, and there's ongoing diversification of ETH holdings. The endowment's recurring revenues now cover 23% of the cash burn.
3. **Revenues and Cash Inflow:** The report shows revenues of $2.0 million, an increase from $1.8 million in the previous month and $2.3 million from the previous year. The cash inflow is recorded at $1.2 million, consistent with the previous month but lower than the $1.7 million from the previous year. The cash inflow is 1.67 times the cash burn.
4. **Cash Burn and Reserves:** The normalized cash burn is $0.7 million, slightly higher than the previous month's $0.6 million but lower than the $0.9 million from last year. The reserves stand at $92 million, up from $85 million in the previous month and significantly higher than the $53 million from the previous year. These reserves include $67 million in ETH and $25 million in USDC.
5. **Endowment Assets and P\&L:** The endowment assets total $64.9 million, with $13.0 million in stablecoins and $51.8 million in ETH. The profit and loss (P\&L) for the period is $5.9 million, primarily from ETH mark-to-market (M2M) gains.

This summary indicates a strong financial position for ENS, with significant reserves, a healthy cash inflow, and a robust endowment, underscoring its sustainability and growth potential. Review the full report prepared by @Steakhouse [here](https://discuss.ens.domains/t/ens-financial-reporting-by-steakhouse/16601/17?u=estmcmxci). — 12.5.23

—

#### Guidelines for Service Provider Streams

In a recent Q\&A session with @AvsA about standards and metrics for the Stream for Providers initiative, it was recommended that Meta-Governance oversee the overall process, with individual streams being managed by the Ecosystem Working Group. The formation of a new working group to handle the Streams Initiative was proposed for next year, but is still up to debate. Service providers are expected to give regular updates; however, if these updates cease, Stewards should step in and halt stream payments. The identity of next year's Stewards is still undetermined, but they will be encouraged to develop their own processes. A minimum one-month interval for updates is suggested to confirm ongoing activity, but Stewards may require more frequent updates as needed. The overarching goal is to enhance the stability and growth of ENS, maintaining leniency to allow all projects to be eligible for the ballot. — 11.28.23

—

#### Update: Name Normalization Refund

In a recent discussion regarding the update and new ETA for Name Normalization, it was revealed that the algorithm for refunding .eth names affected by normalization updates had a minor flaw, which was fortunately identified just before its distribution. To ensure thoroughness, a few more weeks have been allocated, allowing for the detection of any additional issues. The objective remains to complete the distribution before the year's end, though it could potentially be expedited if necessary. — 11.28.23

—

#### **Request for Proposal:** ENS DAO Bylaws

The Meta-Governance working group is seeking proposals from qualified individuals or firms to create comprehensive DAO bylaws for the ENS DAO. These bylaws should be clear, adaptable, and follow best practices, including existing DAO documentation. They will cover aspects like working group operations, voting processes, bylaws amendments, and the DAO's responsibilities. The RFP is open until January 8th, with submissions accepted via DM to @Meta-Gov\_Stewards. After review, the selected party will work with the Meta-Governance Working Group to draft the bylaws for DAO review and adoption through a social vote. — 11.20.23

—

### ☀️ [Public Goods](https://discuss.ens.domains/c/public-goods/37)

**The Public Goods working group hosted its weekly meetings on November 21st, 2023 and November 28th, 2023:**

* [Minutes for Weekly Public Goods Meeting — November 21st](https://discuss.ens.domains/t/public-goods-working-group-weekly-meeting-12pm-et-tuesdays/15982/47?u=estmcmxci)
* [Minutes for Weekly Public Gooods Meeting — November 28th](https://discuss.ens.domains/t/public-goods-working-group-weekly-meeting-12pm-et-tuesdays/15982/48?u=estmcmxci)

—

#### ENS Small Grants Space

Public Goods Steward @vegayp.eth recently hosted a space on X to discuss and inform the community about the ENS Small Grants initiatives which encourages Web3 developers to build open-source projects on ENS. You may review the talk [here](https://x.com/vegaypatino/status/1728902845490229479?s=20). — 11.27.23

—

#### ENS Public Goods Panel Review @ Devconnect

The ENS DAO Public Goods Stewards hosted a panel at NotDEVCON where they discussed the Public Goods grants initiatives, the mission and purpose, the voting process and more. The panel featured past grantees including RevokeCash, Token Engineering Academy, and Clave. Watch highlights from the talk [here](https://x.com/ENS\_DAO/status/1729156149373812750?s=20). — 11.27.23

—

#### ENS DAO Public Goods Working Group Presentations

[**Metagovernance Project**](https://metagov.org/)

A 501(c) non-profit in the US, discussed their work on building infrastructure for digital self-governance and the [State of Web3 Grants report](https://docs.google.com/document/d/1CFD6ztSh2ggJSO-U3uEea92UVB1cRbvBlA1tfPxLKi8/edit#heading=h.awihbcmztvyo), alongside their active contributions to the Web3 space through DAOstars, a subsidiary focusing on [Web3 standards](https://github.com/metagov/daostar/blob/main/DAOIPs/daoip-5.md). They plan to hold a "Web3 Grants Summit" at EthDenver and are engaged in research and technical standards. — 11.30.23

[**Giveth**](https://giveth.io/)

Giveth is conducting ENS-sponsored quadratic funding rounds to support public good projects, [with plans to run multiple rounds simultaneously](https://docs.google.com/document/d/1RMYCrgVXqlJBdaJcc\_mozl1Ob-uKEo9vGA2MzHxwF-U/edit#heading=h.r78rnbl57g2s), similar to Gitcoin's model. They have completed a successful first round and are seeking feedback for future rounds. — 11.30.23

[**Bankless Academy**](https://app.banklessacademy.com/)

Bankless Academy is an interactive Web3 education platform. Independent from BanklessDAO and BanklessHQ, it aids users in building their digital presence and sovereignty, offering lessons on creating Web3 wallets and onboarding to the Optimism network, and aims to extend its outreach within the ENS ecosystem. Each project embodies a facet of the broader goal to support and develop the Web3 ecosystem through education, infrastructure, and community engagement. — 11.30.23

—

### 🌱 [Ecosystem](https://discuss.ens.domains/c/ens-ecosystem/32)

**The Ecosystem working group hosted its weekly meetings on November 23rd, 2023 and November 30th, 2023:**

* [Minutes for Weekly Ecosystem Meeting — November 23rd](https://discuss.ens.domains/t/ens-ecosystem-working-group-weekly-meeting-12pm-et-thursday/15985/99?u=estmcmxci)
* [Minutes for Weekly Ecosystem Meeting — November 30th](https://discuss.ens.domains/t/ens-ecosystem-working-group-weekly-meeting-12pm-et-thursday/15985/101?u=estmcmxci)

> _Note: The ENS Ecosystem Working Group offers rolling grants, and applicants_ [_can apply anytime_](https://app.deform.cc/form/9250f669-ee0e-4e7b-ba5d-5d4eb3813422/)_. The evaluation process takes around four weeks, and unsuccessful applicants are welcome to reapply in the future._

—

#### ENS.js V3 Update

ENS Labs has signaled the imminent launch of ENS.js version 3, boasting enhancements in efficiency, bug fixes, and smoother operation across the Ethereum Name Service (ENS). This update promises to streamline user experiences and provide more robust service capabilities. — 11.28.23

—

#### Louis Vuitton and ENS Collaboration

In a notable collaboration, luxury brand Louis Vuitton has [released an NFT collection](https://twitter.com/opensea/status/1729186834679283973) that utilizes an ENS name, with ENS Labs playing a pivotal role in securing the primary ENS name for this initiative. — 11.28.23

—

#### Project Highlights from ETHGlobal Istanbul Hackathon

Alex Plutta has introduced an ENS Gateway and Verifier on Arbitrum at the ETHGlobal Istanbul Hackathon. This project facilitates the verification of state proofs from contracts on Layer 2 within a Layer 1 context, enhancing cross-chain interactions. — 11.28.23

—

#### The ENS Wayback Machine

Sem Bee's [ENS Wayback Machine](https://wayback-machine.eth.limo/) is a new tool allowing users to travel back in time to explore the history of ENS-linked decentralized applications (dApps), adding a historical dimension to the ENS experience. — 11.28.23

—

#### NameKit Launch by NameHashLabs.org

NameHashLabs.org has launched [NameKit](https://namekit.io/), a tool designed to improve the economics of integrating ENS into applications. This aligns with the goal of making ENS more accessible and ensuring compatibility with other community builders. — 11.28.23 —

#### Expanding the ENS Subdomain Network

The Handle.eth project [aims to create the largest subdomain network](https://twitter.com/dothandle/status/1729885860420821129) within the ENS ecosystem, envisioning it as a marketing powerhouse for ENS and offering free subdomain registrations. — 11.28.23

—

### 📝 [Resources](https://ensdao.org/)

* [ENS DAO Basics](https://basics.ensdao.org/)
* [Support Docs](https://support.ens.domains/docs)
* [Governance Docs](https://docs.ens.domains/v/governance/)
* [ENS Agora](https://agora.ensdao.org/)
* [Give Feedback](https://ens.canny.io)

\--

Thank you very much for reading! Goodbye. 👋🏻
