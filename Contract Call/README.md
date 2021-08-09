# Broaden the Spectrum
## Hackathon: Nervos
### Gitcoin: 3) Issue a Smart Contract Call to the Deployed Smart Contract

- [x] The `transaction hash` from the console output (in text format).
  - `0x80e6b93caaacf0cd9c4e8cb80dd68e57e7279417063aadf488ab1f4ef59b2ef4`

- [x] The contract address that you called (in text format).
  - `0xa5e1d29e7949D46A383C86416356AbB5e291d9ac`

- [x] The ABI for contract you made a call on (in text format).

```json
[
    {
      "inputs": [],
      "stateMutability": "payable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "x",
          "type": "uint256"
        }
      ],
      "name": "set",
      "outputs": [],
      "stateMutability": "payable",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "get",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    }
  ]
```

- [x] A screenshot of the console output immediately after you have successfully issued a smart contract call.

![Call](call.png?raw=true "Call")
