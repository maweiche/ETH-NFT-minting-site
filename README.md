
## buildspace Polygon ENS Mint (Front-End)

![image](/public/image.png)

## Welcome 👋
This is the front-end for a Ethereum NFT mint site. You can see the full project, including how to create and edit the smart contract, on [buildspace](https://buildspace.so/build-nfts).

## How to get things working
To mint your own NFT on Ethereum, change the following:

- Update Contract Address
- Update Front-End ABI File

**Contract Address**
```
/src/App.js
const CONTRACT_ADDRESS = "INSERT_YOUR_DEPLOYED_RINKEBY_CONTRACT_ADDRESS";
```
**ABI File**
```
/src/utils/MyEpicNFT.json
{
    "_format": "hh-sol-artifact-1",
    "contractName": "",
    "sourceName": "",
    "abi": [],
    "bytecode": "",
    "deployedBytecode": "",
    "linkReferences": {},
    "deployedLinkReferences": {}
}
```


## Questions?
Have some questions make sure you head over to your [buildspace Dashboard](https://buildspace.so/p/mint-nft-collection) and link your Discord account so you can get access to helpful channels and your instructor!