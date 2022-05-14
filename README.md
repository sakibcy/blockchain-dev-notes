# Blockchain Development Notes

* [Changing version of Solidity](https://github.com/sakibcy/blockchain-dev-notes#changing-version-of-solidity) 

### Changing version of Solidity
```solidity
pragma solidity ^0.8.0; // change version here first
```

#### Change the compiler version in VS code
<img src='./images/changeSolidityVersionVSCode.png' />

#### Change the version on ```javascript truffle-config.js```
```javascript
compilers: {
    solc: {
      version: "0.8.0", // here
      optimizer: {
        enabled: true,
        runs: 200,
      },
```
