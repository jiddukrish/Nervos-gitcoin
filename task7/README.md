### TASK7


- ### Screenshots/Video

👉 Click one of the image to see project video

[![Project Video](https://github.com/jiddukrish/Nervos-gitcoin/blob/master/task7/nervos1.png)](https://youtu.be/5rPvHL6OS2U)

<hr/>

[![Project Video](https://github.com/jiddukrish/Nervos-gitcoin/blob/master/task7/nervos2.png)](https://youtu.be/5rPvHL6OS2U)

- ### Link to the GitHub repository

<a href="https://github.com/jiddukrish/nervos-kickstarter-task7" target="_blank">GITHUB REPO</a>

- ### Transaction hash, deployed contract address, ABI of the deployed smart contract

Transaction Hash: ```0x757c502df4d0b165fd42ee5b930954ccfedb334a0ad8a828331eaec9ebca9cb3```

Deployed Contract Address: ```0x675018732426094bE7dABB55Bd7F3f3aa5B7D991```

ABI:

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
