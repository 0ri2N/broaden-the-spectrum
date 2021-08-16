# Broaden the Spectrum
## Hackathon: Nervos
### Gitcoin: 7) Port an Existing Ethereum dApp to Polyjuice

- [x] Link to the GitHub repository with your application which has been ported to Godwoken. **This must be a different application than the one covered in this guide.**
  - **Repository:** https://github.com/ririen/fancy-names
  - **Live deploy:** http://fancy-names.vercel.app/ 

- [x] Screenshots or video of your application running on Godwoken.

![DApp 1](dapp-1.png?raw=true "DApp 1")
![DApp 2](dapp-2.png?raw=true "DApp 2")

- [x] If you deployed any smart contracts as part of this tutorial, please provide the transaction hash of the deployment transaction, the deployed contract address, and the ABI of the deployed smart contract. (Provide all in text format.)
  - Deployment transaction: `0xa13e4a5a6ec5d6a0cd03416d5c73956f5152cc6ff4d3e63366330c4129eb01de`
  - Deployment contract address: `0xFB5E7347bA0da2d7471E41FAE2308f3eeDE91288`
  - Deployment ABI:

```json
[
    {
      "inputs": [
        {
          "internalType": "address",
          "name": "",
          "type": "address"
        }
      ],
      "name": "claimers",
      "outputs": [
        {
          "internalType": "bool",
          "name": "claimed",
          "type": "bool"
        },
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "name",
          "type": "string"
        }
      ],
      "name": "claim",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "read",
      "outputs": [
        {
          "internalType": "string",
          "name": "",
          "type": "string"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```