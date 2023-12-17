# Metaplex Candy Machine Reference UI

## Project Title

The Metaplex Candy Machine Reference UI serves as the user interface for the Candy Machine Minting Setup.

## Description

The primary purpose of this interface is to facilitate the minting of NFTs by users.

## Getting Started

To begin, follow these steps:

1. Install the required dependencies using yarn:

   ```bash
   yarn install
   ```

2. Start the application:

   ```bash
   yarn start
   ```

## Executing Program

Before executing the program, create a `.env` file with the following configurations:

```dotenv
REACT_APP_CANDY_MACHINE_ID=<YOUR_CANDY_MACHINE_PUBKEY>
REACT_APP_SOLANA_NETWORK=devnet
REACT_APP_SOLANA_RPC_HOST=<YOUR_QUICKNODE_DEVNET_ENDPOINT>
```

If you've forgotten your Candy Machine ID, you can locate it in `cache.json` under the `program.candyMachine` field.

To mint an NFT, ensure you have devnet SOL in your Phantom wallet. You can use the Solana CLI to airdrop SOL to your Phantom wallet with the following command:

```bash

solana airdrop 1 YOUR_PHANTOM_WALLET_ADDRESS
```

Feel free to reach out if you encounter any issues or require further assistance. Happy minting!
