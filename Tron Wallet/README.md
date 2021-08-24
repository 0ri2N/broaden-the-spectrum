# Broaden the Spectrum
## Hackathon: Nervos
### Gitcoin: 11) Use a Tron Wallet to Execute a Smart Contract Call

_Some of the tasks have already been done in previous issues. The complete list of completed tasks can be found here: [Main Repo](../README.md)._

- [x] A screenshot of the accounts you created (`account list`) in `ckb-cli`.

![Accounts](../Godwoken%20Account/accounts.png?raw=true "Accounts")

- [x] A link to the Layer 1 address you funded on the Testnet Explorer.
  - https://explorer.nervos.org/aggron/address/ckt1qyqgaqaufmjcpu3kfmklslft809qkxdhdgwqdk3sks

- [x] A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2.

![Tron Deposit](tron-deposit.png?raw=true "Tron Deposit")

- [x] A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2.

![Tron Call](tron-call.png?raw=true "Tron Call")

- [x] The `transaction hash` of the "Contract call" from the console output (in text format).
  - `0x25f9b816b5d11c27aa6eccd535c05131fe6ad641f2cd6899c7433f80354e3a36`

- [x] The `contract address` that you called (in text format).
  - `0xa5e1d29e7949D46A383C86416356AbB5e291d9ac`
  - _This is the contract that was created during the execution of task 2 here: [Smart Contract](../Smart%20Contract/README.md)_

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

- [x] Your Tron address (in text format).
  - `TCEPv6StBXHWSLoCST8FpBuPCJiFjvnx4X`