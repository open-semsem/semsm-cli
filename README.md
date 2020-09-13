# semsm-cli
=========
A utility for auto generate web3 functions from any truffle smart contracts
# to use
- as truffle plugin :
  - add the package to your truffle project `npm install @semsm/semsm-cli` 
  - add the plugin to `truffle-config.js` ` plugins: [
     plugins: [
    '@semsm/semsm-cli'
  ]`
  - `truffle run generate`
  - or `truffle run generate -d YOUR_ARTIFACT_PATH  -p YOUR_PROVIDER `
- as node package 
  - `npm install @semsm/semsm-cli`
  - `semsm  -d YOUR_ARTIFACT_PATH  -p YOUR_PROVIDER `
  - you can use it inside any truffle project , run `truffle migrate`  then `semsm ` it will take the default contract artifacts you can spacify the provider through this flag `--provider` or `-p` otherwise , it will take the default `http://127.0.0.1:8545` 



# Credits
This cli is based on [@semsm/semsm-cli](https://github.com/EmanHerawy/truffle-service-generator)

