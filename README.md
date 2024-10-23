# WalletX SDK

WalletX aims to revolutionize the Web3 ecosystem by removing barriers to entry and enhancing user accessibility through innovative, gasless solutions.

Working towards our vision, WalletX brings WalletX SDK.

This SDK is built to provide the world's first invisible wallet for the dApps to integrate for their users.

WalletX SDK removes the barrier of using wallets and dApps separately, enhancing the user experience and making users feel the real power of any dApp without even knowing about a Wallet.

dApps can simply integrate WalletX SDK which will allow the dApps to provide their users with non-custodial invisible wallets.

This will not only enhance the user experience but will also help dApps to focus on their users providing them will the best solutions.

## Steps to integrate

1. Create a `.npmrc` file in the root folder of your project with the following content.

```
@getwalletx:registry=https://registry.npmjs.org/
package-lock=false
//registry.npmjs.org/:_authToken=${ACCESS_TOKEN}
```

2. Install the package in your dApp

```
npm i @getwalletx/walletx-sdk
```

3. Import package

```
import WalletX from "@getwalletx/walletx-sdk";
```

4. Create the wallet instance

```
const Wallet = new WalletX();
```

5. Initialize the wallet

```
await Wallet.initWallet();
```

And there you have it!!!

The wallet user wallet is not created that is fully non-custodial and managed using the user's browser storage.

##

#### Note

Step 1 is required because the package is deployed on the private registry ensuring better collaboration with the dApps.

To get the `ACCESS_TOKEN`, kindly reach out to team **_WalletX_** via [X](https://x.com/getWalletX), [Telegram](https://t.me/getwalletx), [Discord](https://discord.gg/9ZpJ7JMu)
