<<<<<<< HEAD
# For deta Wallet DAPP Developer

## Using deta Wallet Filecoin JS API

### Samples

```

// login
// returns { "name": "test1", "address": "t1u3ynne5fllqpv4re5vkqbvowtsb2aggh2p4u5fa"}
const account = await window.filecoin.login();

// logout
// returns {}
await window.filecoin.logout();

// SendTransaction
const transaction =  {
        from: this.account.address,//account address
        gasPremium: "10000",//Optional type(String)
        gasFeeCap:"10000",//Optional type(String)
        nonce: 0,//Optional type(Number)
        gasLimit: 2200000,
        to: "t1uzmmfknk3pq5otq4wosqtzm3oq7675vb27qz6aq",//String
        value: "1000000000000000000", // decimals 18,String
        method: 0,
        params: ""
      };
await window.filecoin.sendTransaction(transaction);

// RequestSignature
const transaction =  {
        from: this.account.address,//account address
        gasPremium: "10000",//String
        gasFeeCap:"10000",//String
        nonce: 0,//Number
        gasLimit: 2200000,
        to: "t1uzmmfknk3pq5otq4wosqtzm3oq7675vb27qz6aq",//String
        value: "1000000000000000000", //decimals 18,String
        method: 0,
        params: ""
      };
await window.filecoin.requestSignature(transaction);

```
For details, please find the sample in this repo.

### Download deta Wallet 麦子钱包下载

[http://detawallet.org](http://detawallet.org)
=======
# For Delta Wallet DAPP Developer

## Using  Delta Wallet Filecoin JS API

>>>>>>> 7a9db81ce051d50a536b4cadce6dfcda0e90bf44


