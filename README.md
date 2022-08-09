# BuyMeACoffeeWebsite

Frontend of the BuyMeACoffee Dapp built with Replit, Ethers.js, and React. Based of the Smart Contract backend code of 
<a href="https://github.com/AhaanKanaujia/BuyMeACoffee" target="_blank">BuyMeACoffee</a>. 

To customize the website to load info from your own contract, change the following:

- Update `contractAddress` in `pages/index.js` to your own BuyMeACoffee contract on the Goerli testnet.
- Update `utils/BuyMeACoffee.json` to match the json artifact for your contract after compilation.
- Update the name and footer text in `pages/index.js` to your own name and info.

Install Dependencies:

```
npm install
```

Run the Development Sever:

```
npm run dev
```

The app is deployed to http://localhost:3000/, where you can connect your wallet and send tips to the user on a test network. 
