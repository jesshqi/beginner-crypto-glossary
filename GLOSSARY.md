# Beginner Crypto Glossary

Plain-English definitions. No jargon, no assumptions.

## Wallet

An app (or device) that holds your crypto. It stores your keys and
lets you send, receive, and sign transactions. Your coins are not
"inside" the wallet — they live on the blockchain. The wallet just
holds the keys that control them.

## Seed phrase (recovery phrase)

12 or 24 words that can restore your entire wallet. **Whoever has
your seed phrase owns your wallet.** Write it on paper, store it
offline, and never share it with anyone — not a website, not support,
not a friend. No legitimate service will ever ask for it.

## Private key

A long secret number that proves you own a wallet address. Like a
seed phrase, it must stay secret. A seed phrase can generate many
private keys; a private key controls one address.

## Public address

Your wallet's public identifier, starting with `0x...`. You share
this freely — it is how people send you tokens. Knowing an address
does **not** let anyone spend your funds.

## Blockchain

A public ledger shared by many computers. Every transaction is
recorded there and cannot be changed afterwards.

## Mainnet

The real blockchain, where tokens have real value. Mistakes here cost
real money.

## Testnet

A copy of a blockchain where tokens are free and worthless. Use it to
learn and test. The most common ones are Ethereum Sepolia and Base
Sepolia. See
[testnet-starter-kit](https://github.com/jesshqi/testnet-starter-kit).

## Gas

The fee you pay for a transaction, measured in the chain's native
token (ETH on Ethereum, BNB on BSC). Gas is paid to the network, not
to the project you are using.

## Faucet

A website that gives out small amounts of free test tokens so you can
practice on a testnet. Real faucets only ask for your public address.

## Token

A digital asset on a blockchain. The two common standards are:

- **ERC-20** — fungible tokens (every unit is identical), for example
  stablecoins and most project tokens.
- **ERC-721** — non-fungible tokens (NFTs), where each token is unique.

## NFT

A unique token (ERC-721 or ERC-1155) that represents ownership of one
specific item — art, a collectible, a pass. Each NFT has a token id
and an owner.

## Smart contract

A program that lives on the blockchain. Once deployed, it runs exactly
as written and cannot be changed (unless it was built to be
upgradeable).

## Mint

To create a new token or NFT. A "free mint" should cost 0 (value 0 +
gas only). If a "free" mint charges a mandatory fee, it is not free.

## Approval / allowance

Permission you give a contract to move your tokens or NFTs. An
**unlimited** approval lets it move any amount until you revoke it.
Check yours with
[token-approval-checker](https://github.com/jesshqi/token-approval-checker),
and revoke approvals you no longer need.

## DYOR

"Do Your Own Research." Before you mint, buy, or connect your wallet,
verify the project's website, contract, team, and community yourself.
