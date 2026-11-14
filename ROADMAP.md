# Beginner Crypto Roadmap

A suggested path from zero to confident. Go at your own pace — there
is no deadline, and skipping steps is how people lose money.

## Step 1 — Learn the basics (no money involved)

- Read the [glossary](GLOSSARY.md). Know what a wallet, seed phrase,
  gas, and approval are before you touch anything.
- Understand this rule: **your seed phrase is your wallet.** Anyone
  who has it owns everything in it.

## Step 2 — Set up a wallet

- Install a wallet app (for example MetaMask).
- Write your seed phrase on paper and store it offline. Never type it
  into a website.
- Use a **separate wallet for experiments**. Keep your main wallet
  apart from testnets and free mints.

## Step 3 — Practice on a testnet (free)

- Get free test ETH from a faucet and check your balance. See
  [testnet-starter-kit](https://github.com/jesshqi/testnet-starter-kit).
- Send a small test transaction to yourself. Watch it on the testnet
  explorer. Learn what gas is and how long a transaction takes.
- Nothing here has real value, so mistakes are free.

## Step 4 — Learn to verify before you mint

- Before any "free" mint, check the contract first with
  [free-mint-safety-checker](https://github.com/jesshqi/free-mint-safety-checker):
  does it have code, is the source verified, what can the owner do?
- Confirm the mint price is really 0 (value 0 + gas only).
- Check the project has a real website and a public team/community.

## Step 5 — Understand approvals

- Learn what an approval is and why unlimited approvals are risky.
- Check what you have approved with
  [token-approval-checker](https://github.com/jesshqi/token-approval-checker).
- After minting or listing, check your approvals and revoke the ones
  you no longer need.

## Step 6 — Read a wallet, then build

- Learn to read what a wallet holds with
  [bsc-wallet-checker](https://github.com/jesshqi/bsc-wallet-checker)
  (BNB, token balances, NFT owners).
- When you are ready to build, start with
  [first-nft-contract](https://github.com/jesshqi/first-nft-contract)
  — a commented ERC-721 you can deploy on a testnet for free.

## Safety rules (all steps)

1. Never share your seed phrase or private key. Ever.
2. Never pay for test tokens. They are free.
3. A "free" mint with a mandatory fee is not free.
4. If a project has no official website, treat it with extra caution.
5. DYOR — verify the website, contract, team, and community yourself.
