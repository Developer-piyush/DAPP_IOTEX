# Demo Video: [link](https://youtu.be/G5hruRV4764)
# App link: [click here](https://socialnetwork-ebon.vercel.app/)
## ```"Decentralized Social Network on IoTeX Blockchain."```
![iotex](https://github.com/Developer-piyush/DAPP_IOTEX/blob/main/images/IOTEX.png)



## Instructions to run this app in your local machine

<hr>
make sure you have some tokens in your metamask wallet (iotex and ropsten)
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


To deploy on Iotex testnet run
```
truffle migrate --reset --network dev
```

To deploy on Iotex mainnet run
```
truffle migrate --reset --network devmain
```

To start the server
```
npm run start
```
starts the server at http://localhost:30000
