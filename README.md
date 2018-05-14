
WORK-IN-PROGRESS / DRAFT - WORK-IN-PROGRESS / DRAFT - WORK-IN-PROGRESS / DRAFT

# Mastering Ethereum - Building Blockchain Service Contracts and Decentralized Apps

by [Andreas M. Antonopoulos](https://github.com/aantonop), [Gavin Wood](https://github.com/gavofyork)


> Note: This is the original source reformatted in a single-page book edition
>  (using the [Manuscripts format](http://manuscripts.github.io)).



- [What is Ethereum?](manuscript/what-is.md)
  - [Compared to Bitcoin](manuscript/what-is.md#compared-to-bitcoin)
    - [Components of a blockchain](manuscript/what-is.md#components-of-a-blockchain)
  - [Development of Ethereum](manuscript/what-is.md#development-of-ethereum)
  - [The birth of Ethereum](manuscript/what-is.md#the-birth-of-ethereum)
  - [Ethereum's four stages of development](manuscript/what-is.md#ethereums-four-stages-of-development)
    - [Past transitions](manuscript/what-is.md#past-transitions)
    - [Current state](manuscript/what-is.md#current-state)
    - [Future plans](manuscript/what-is.md#future-plans)
  - [Ethereum: A general purpose blockchain](manuscript/what-is.md#ethereum-a-general-purpose-blockchain)
  - [Ethereum's components](manuscript/what-is.md#ethereums-components)
    - [Further references](manuscript/what-is.md#further-references)
  - [Ethereum and Turing Completeness](manuscript/what-is.md#ethereum-and-turing-completeness)
    - [Turing Completeness as a "feature"](manuscript/what-is.md#turing-completeness-as-a-feature)
    - [Implications of Turing Completeness](manuscript/what-is.md#implications-of-turing-completeness)
  - [From general purpose blockchains to Decentralized Applications (DApps)](manuscript/what-is.md#from-general-purpose-blockchains-to-decentralized-applications-dapps)
  - [Evolving the World Wide Web](manuscript/what-is.md#evolving-the-world-wide-web)
  - [Ethereum's development culture](manuscript/what-is.md#ethereums-development-culture)
  - [Why learn Ethereum?](manuscript/what-is.md#why-learn-ethereum)
  - [What this book will teach you?](manuscript/what-is.md#what-this-book-will-teach-you)
- [Tokens](manuscript/tokens.md)
  - [What are tokens?](manuscript/tokens.md#what-are-tokens)
  - [How are tokens used?](manuscript/tokens.md#how-are-tokens-used)
  - [Tokens and fungibility](manuscript/tokens.md#tokens-and-fungibility)
  - [Counterparty risk](manuscript/tokens.md#counterparty-risk)
  - [Tokens and intrinsicality](manuscript/tokens.md#tokens-and-intrinsicality)
  - [Using tokens: utility or equity](manuscript/tokens.md#using-tokens-utility-or-equity)
    - [It's not a duck](manuscript/tokens.md#its-not-a-duck)
     - [Utility tokens: who needs them?](manuscript/tokens.md#utility-tokens-who-needs-them)
  - [Token Standards](manuscript/tokens.md#token-standards)
    - [ERC20 Token Standard](manuscript/tokens.md#erc20-token-standard)
      - [ERC20 required functions & events](manuscript/tokens.md#erc20-required-functions--events)
      - [ERC20 optional functions](manuscript/tokens.md#erc20-optional-functions)
      - [The ERC20 interface defined in Solidity](manuscript/tokens.md#the-erc20-interface-defined-in-solidity)
      - [ERC20 data structures](manuscript/tokens.md#erc20-data-structures)
      - [ERC20 workflows: "transfer" and "approve & transferFrom"](manuscript/tokens.md#erc20-workflows-transfer-and-approve--transferfrom)
      - [ERC20 Implementations](manuscript/tokens.md#erc20-implementations)
    - [Launching our own ERC20 token](manuscript/tokens.md#launching-our-own-erc20-token)
    - [Interacting with METoken using the truffle console](manuscript/tokens.md#interacting-with-metoken-using-the-truffle-console)
    - [Sending ERC20 tokens to contract addresses](manuscript/tokens.md#sending-erc20-tokens-to-contract-addresses)
    - [Demonstrating the approve & transferFrom workflow](manuscript/tokens.md#demonstrating-the-approve--transferfrom-workflow)
    - [Issues with ERC20 tokens](manuscript/tokens.md#issues-with-erc20-tokens)
    - [ERC223 - a proposed token contract interface standard](manuscript/tokens.md#erc223---a-proposed-token-contract-interface-standard)
    - [ERC777 - a proposed token contract interface standard](manuscript/tokens.md#erc777---a-proposed-token-contract-interface-standard)
    - [ERC721 - non-fungible token (deed) standard](manuscript/tokens.md#erc721---non-fungible-token-deed-standard)
  - [Token standards](manuscript/tokens.md#token-standards-1)
    - [What are token standards? What is their purpose?](manuscript/tokens.md#what-are-token-standards-what-is-their-purpose)
    - [Should you use these standards?](manuscript/tokens.md#should-you-use-these-standards)
  - [Security by maturity](manuscript/tokens.md#security-by-maturity)
  - [Extensions to token interface standards](manuscript/tokens.md#extensions-to-token-interface-standards)
  - [Tokens and ICOs](manuscript/tokens.md#tokens-and-icos)




## Meta

### Sources

See the [original source](https://github.com/ethereumbook/ethereumbook) repo.
