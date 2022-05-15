# Blockchain Development Notes

* [Changing version of Solidity](https://github.com/sakibcy/blockchain-dev-notes#changing-version-of-solidity) 
* [Usefull Package Manager](https://github.com/sakibcy/blockchain-dev-notes#usefull-package-manager)
* [Ethereum Concepts](https://github.com/sakibcy/blockchain-dev-notes#ethereum-concepts)

## Changing version of Solidity

#### Change version here first
```solidity
pragma solidity ^0.8.0; 
```

#### Change the compiler version in VS code
<img src='./images/changeSolidityVersionVSCode.png' />

#### Change the version on ```truffle-config.js```
```javascript
compilers: {
    solc: {
      version: "0.8.0", // here
      optimizer: {
        enabled: true,
        runs: 200,
      },
```

## Set Truffle to compile Js
#### Add a bable-preset-env and bable-preset-stage
A Babel preset that compiles ES2015+ down to ES5 by automatically determining the Babel plugins and polyfills you need based on your targeted browser or runtime environments.
#### Install babel-preset-env
```sh
npm i @babel/preset-env
```

#### Install babel-preset-stage 
```sh
npm i babel-preset-stage-2
```

#### Add ```.babelrc``` file on the project root directory and add those
```json
{
  "presets": ["env", "stage-2"]
}
```

## Usefull Package Manager
* <a href="https://www.npmjs.com/package/@openzeppelin/contracts" target="_blank">OpenZeppelin Contracts</a>
    * A library for secure smart contract development. Build on a solid foundation of community-vetted code.

## Ethereum Concepts
* <a href="https://academy.binance.com/en/glossary/gwei" target="_blank">Gwei</a>
