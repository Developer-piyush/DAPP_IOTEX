## ```"Decentralized Social Network on IoTeX Blockchain."```
![iotex](https://github.com/Developer-piyush/DAPP_IOTEX/blob/main/images/IOTEX.png)

[link to app](socialnetwork-ebon.vercel.app)
## after confirming transaction, refresh the page.
## Instructions to run this app in your local machine
<hr>
Change babelrc and env to .babelrc & .env <br>
fill in private key and infura api key in .env
<hr>
Install dependencies
```
npm install
```

```
npm install @truffle/hdwallet-provider
```

Now make sure you have some tokens in your metamask wallet (iotex and ropsten)

To deploy on Iotex testnet run
```
truffle migrate --reset --network dev
```

To deploy on ropsten testnet run
```
truffle migrate --reset --network ropsten
```

To start the server
```
npm run start
```
starts the server at http://localhost:30000
