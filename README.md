# Uniswap token trade 

Our goal for this repo is to achieve the trade off between two tokens to the lowest possible values through UNISWAP V3 Router in `node.js` 


<br>



# Installation

1. It is recommended to have some basic understanding of interaction with smart contracts through ABI making and making instances of contracts through Web3.js or ethers.js SDK:
2. Run: `npm i` which will install the following npm packges  `ether`,  `@uniswap/sdk-core`,  `@uniswap/v3-sdk`, and `dotenv`.
3. Accept all options and let the requirements install
4. Add an `.env` file in the root directory.
5. Make sure you are in the `gametokenUniswaptrade1` directory.
6. Make sure your wallet secret key, wallet address and infura test url are filled  `.env` file (see below).
7. make sure you have the same  private RPc node for pair of tokens where you want to trade and filled in `.env` file as below.

<br>

# .env Key Fields

<ins>Development Key Fields</ins>
- Binance:
  - `INFURA_URL=<infura url>`
   - `WALLET_SECRET =<wallet private key>`
   - `WALLET_ADDRESS =<wallet public key>`
  you can learn how to have your public cnad private key from `Metmask` https://www.youtube.com/watch?v=qsvwg-cC928
  

<br>

# Usage

### Option 1: Running 

1. Make sure you are in the `gametokenUniswaptrade1` directory.
2. Run `node` on `uniswapGameToUsdt.js` to trade Game token over USDT.
3. Run `node` on `uniswapUsdToGame.js` to trade USDT token over Game.
3. TO know the pool addresse, Run `node` on `getUniswapPool.js`, copy the address from console or return to as output.

<br>

# Key Files and Folders
-  (`gametokenUniswaptrade1/uniswapGameToUsdt.js`)
   -Trades Game over USDT
- (`gametokenUniswaptrade1/uniswapUsdToGame.js`)
   - Trades USDT over Game.
- (`gametokenUniswaptrade1/getUniswapPool.js`)
   -Get you pool address of any two tokens (if exist).
- Models (`gametokenUniswaptrade1/helpers.js`)
   - Where some generic functions are described

<br>

# Resources
- UNISWAP Router -https://docs.uniswap.org/protocol/reference/deployments
- What is an ABI -https://www.quicknode.com/guides/solidity/what-is-an-abi
- How to create instance of smartcontraact with ethers.js sdk -https://docs.ethers.io/v5/api/contract/contract/
- Wallet instances in ethers.js SDK - https://docs.ethers.io/v5/api/signer/#Wallet-constructor

<br>

# Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
ng the pool
