# TrustWeb3Provider


ONTOWeb3Provider currently bundles [web3 0.20.x](https://github.com/trustwallet/trust-web3-provider/blob/master/src/package.json#L22), we will follow MetaMask proposal: [No Longer Injecting web3.js](https://medium.com/metamask/no-longer-injecting-web3-js-4a899ad6e59e).

## How to Identify Trust Provider

If trust provider injected properly `isONTO` will be `true`

```javascript
window.ethereum.isONTO
```

## Installation

```
npm install
```

## Build
```
npm run build
```

## License

ONTOWeb3Provider is available under the MIT license. See the LICENSE file for more info.
