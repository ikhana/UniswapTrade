# Basic Sample Hardhat Project

This project demonstrates a simple script to trade two tokens via uniswap through node.js.

To accomplish the task we need 4 addresses:
1) address of the firt token 
2) address of  the second token 
3) Uniswap Router address which can be found in uniswap docs
4) Pool address => Can be get by running the getUniSwapPool.js file provided the address of the first token and address of the second token. Once done with that you can paste the adress from command line into uniswpGameToUsdt.js or uniswapUsdtToGame.js to achieve the alternative trade. Or you can call the function from getUniSwapPool.js and get the address automatically into these two file. 

```shell
node getUniSwapPool.js
node uniswapUsdtToGame.js
node uniswpGameToUsdt.js
```

Make sure you have the right addresses and same infura url  when getting the pool
