# dexfair
# Introduction
- The dexfair is a swap service that can exchange erc20 tokens.
- And users can also provide liquidity to earn rewards.

# Environment
- The dexfair can be used on both desktop and mobile.
- It can be used through MetaMask desktop, MetaMask mobile, and dexfair dappbrowser under development.

## Desktop
- You need a web browser with [MetaMask desktop extension wallet](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn) or [DSRV desktop extension wallet](https://chrome.google.com/webstore/detail/celo-desktop-wallet/kkilomkmpmkbdnfelcpgckmpcaemjcdh) installed.


## Mobile
- MetaMask mobile app is required.
- [android](https://play.google.com/store/apps/details?id=io.metamask&hl=ko&gl=US)
- [ios](https://apps.apple.com/us/app/metamask/id1438144202)

# Usage
1. Enter https://dexfair.github.io/ in the address bar on both desktop and mobile.
2. Network Change to Alfajores.
3. If there are not enough celo on the testnet, the celo is charged [here](https://celo.org/developers/faucet).

![desktop](https://user-images.githubusercontent.com/57783762/99212723-2d073680-280f-11eb-979f-d1d837df9642.png)
![mobile](https://user-images.githubusercontent.com/57783762/99212725-2ed0fa00-280f-11eb-850f-f428c6c65288.png)

## Tabs
- Transfer
  - Tokens can be transferred using Metamask and DSRV's wallet in a desktop environment.
  - You can use CELO and cUSD, and It can be transferred all tokens that support ERC20.
    - The user enters the type and amount of tokens to send,
    - Enters the recipient's address,
    - And then presses the transfer button.
    - Press the button to open the wallet, and press the check signature button on the wallet.
    - when the transfer is complete, check in Block Explorer.

- Exchange (mainnet)
  - This is the default EXCHANGE supported by CELO.
    - Decide which token you want to exchange and the amount.
    - Check the amount.
    - Click the exchange button.
    - The subsequent process is the same as the transfer process.
  - When using it for the first time, you have to click the Approve button.
    - If the amount to be exchanged falls below the slippage value, the transaction fails.
    
- dexfair (testnet)
  - It is an exchange of dexfair.
  - It has the same UI as the default exchange.
    - It is handled in the same UI/UX as the default exchange.
  - The currency exchange formula is also the same as the default exchange.
  - Instead, the applied settings have slippage and time limit.
    - If the transaction is not processed within the timeout period, the exchange will fail.

- Liquidity (testnet)
  - Supply liquidity.
    - Select the 2 types of tokens you want to supply liquidity.
    - Determine the amount of each token.
    - Press the Mint liquidity button.
    - Repeat the same process of getting a signature from your wallet.
  - Remove liquidity.
    - You decide how much of your stake you want to burn.
    - Press the Burn button.
    - Repeat the same process of getting a signature from your wallet.
    - The formula is the same as for regular swap.

- Setting
  - This is where you adjust the settings to be used in Exchange.
  - In the default Exchange, only Slippage can be adjusted.
