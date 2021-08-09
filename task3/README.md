1. A screenshot of the console output immediately after you have successfully issued a smart contract call.

![issue](./issue.png)

2. The transaction hash from the console output (in text format).

```
0x673fae21ccf11f613fd8f509681ae583467ea814d10797f53c4774b48a1aba76
```

3. The contract address that you called (in text format).

```
0x0EAB61bb763BD359a951333Dbcaa6529812818aE
```

4. The ABI for contract you made a call on (in text format).
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