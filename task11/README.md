### Gitcoin: 11) Use A Tron Wallet To Execute A Smart Contract Call

- ### A screenshot of the accounts you created

<img src="https://github.com/jiddukrish/Nervos-gitcoin/blob/master/task11/screenshot1.jpg"/>

- ### A link to the Layer 1 address you funded on the Testnet Explorer

<a href="https://explorer.nervos.org/aggron/address/ckt1qyqqhmyytzcqp5j4vpmdarjl3kz70dh3m8tsps7ay9"> Testnet account link </a>

- ### A screenshot of the console output immediately after you have successfully submitted a CKByte deposit to your Tron account on Layer 2

<img src="https://github.com/jiddukrish/Nervos-gitcoin/blob/master/task11/screenshot2.png"/>

- ### A screenshot of the console output immediately after you have successfully issued a smart contract calls on Layer 2

<img src="https://github.com/jiddukrish/Nervos-gitcoin/blob/master/task11/screenshot3.png"/>

- ### The transaction hash from the console output

```0x5cad923cf297236d9eea0d946e9195885812791291b9ad7cf4092ffb2f2b9d74```

- ### The contract address that you called

```0x675018732426094bE7dABB55Bd7F3f3aa5B7D991```

- ### The ABI for contract you made a call on

```javascript
[
    {
      "inputs": [],
      "stateMutability": "nonpayable",
      "type": "constructor"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "name": "projects",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "id",
          "type": "uint256"
        },
        {
          "internalType": "string",
          "name": "title",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "description",
          "type": "string"
        },
        {
          "internalType": "uint256",
          "name": "votes",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "totalProject",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [],
      "name": "getTotalProjects",
      "outputs": [
        {
          "internalType": "uint256",
          "name": "",
          "type": "uint256"
        }
      ],
      "stateMutability": "view",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "string",
          "name": "_title",
          "type": "string"
        },
        {
          "internalType": "string",
          "name": "_description",
          "type": "string"
        }
      ],
      "name": "createProject",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    },
    {
      "inputs": [
        {
          "internalType": "uint256",
          "name": "_projectId",
          "type": "uint256"
        }
      ],
      "name": "vote",
      "outputs": [],
      "stateMutability": "nonpayable",
      "type": "function"
    }
  ]
```

- ### Your Tron address

```TAb8pjDEkBjczG6afyWzhkE83pHYPrGRvh```









