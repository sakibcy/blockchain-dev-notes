# Blockchain Development Notes

### Changing version of Solidity
```solidity
pragma solidity ^0.8.0; // change version here first
```

change the compiler version in VS code

change the version on truffle-config.js
```javascript
compilers: {
    solc: {
      version: "0.8.0", // here
      optimizer: {
        enabled: true,
        runs: 200,
      },
```
