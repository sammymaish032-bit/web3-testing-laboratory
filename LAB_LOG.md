# Lab 02: Public Sepolia Testnet Transactions

## Objective
Practice receiving test ETH from a faucet, sending ETH between MetaMask accounts, and independently verifying transactions on a public Ethereum testnet.

## Environment
- Wallet: MetaMask
- Network: Ethereum Sepolia
- Chain ID: 11155111
- Explorer: https://sepolia.etherscan.io/

## Wallets
- Sender: Account 1 — `0x6dD3C912151086c805bBaC90fCB981978847C630`
- Recipient: Account 2 — `0x08B6Cc621c1da5d09E31a043E427676F69592817`

## Exercise 1: Receive test ETH
- Received: 0.05 Sepolia ETH
- Status: Success
- Block: 12066831
- Transaction hash: `0x92924bda73e4d870c7e4806f1d8d813f544b0d8d66c8e81f53a6c2bab6ca42c1`

## Exercise 2: Transfer ETH
- Sender: Account 1
- Recipient: Account 2
- Amount: 0.1 Sepolia ETH
- Status: Success
- Block: 12066867
- Confirmations observed: 10
- Gas price: 1.500000016 Gwei
- Transaction fee: 0.0003069000032736 ETH
- Transaction hash: `0x2ba6decd8aa7ebf8989823ff0ae3dd28621fbe35b5b5fa3cd4079e11610df7fd`

## Verification
- Both transactions were visible on Sepolia Etherscan.
- The outgoing transfer showed Success.
- Account 2 received 0.1 ETH.
- Account 1's balance decreased by the transferred amount plus the transaction fee.
- Both wallet balances matched the expected transaction results.

## Concepts Learned
1. Public testnets allow transactions to be independently inspected.
2. Wallet addresses identify the sender and recipient.
3. Transaction hashes identify individual blockchain transactions.
4. Block explorers expose transaction status and execution details.
5. Gas fees are separate from the ETH transferred.
6. Transaction confirmation means the transaction was included in a block.
7. Testnet ETH has no real-world monetary value.

## Outcome
Successfully completed a public Sepolia ETH transfer and verified its execution and balance effects.
