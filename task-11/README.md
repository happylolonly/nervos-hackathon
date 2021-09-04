# Use A Tron Wallet To Execute A Smart Contract Call

https://gitcoin.co/issue/nervosnetwork/grants/15/100026366

1. CKB accounts [](./accounts.png)
2. Layer 1 address - `https://explorer.nervos.org/aggron/address/ckt1qyqxk8nhv5jjxva3qetn8wjgccfqlxxrrt9qt3uy7t`
3. CKByte deposit to Tron account on Layer 2 [](./deposit.png)
4. Smart contract calls on Layer 2 [](./calls.png)
5. Transaction hash of the "Contract call" - `0x91c374289f2115b5c6a1de7c991c1d1f4b018b1aefd8d7b722e5168e5b86f11a`
6. Contract address called - `0xc413013fBf437Ba31232C2bb9eFd2e05A03DfD1f`
7. ABI for contract:

```
[
  {
    inputs: [],
    stateMutability: "payable",
    type: "constructor",
  },
  {
    inputs: [
      {
        internalType: "uint256",
        name: "x",
        type: "uint256",
      },
    ],
    name: "set",
    outputs: [],
    stateMutability: "payable",
    type: "function",
  },
  {
    inputs: [],
    name: "get",
    outputs: [
      {
        internalType: "uint256",
        name: "",
        type: "uint256",
      },
    ],
    stateMutability: "view",
    type: "function",
  },
]
```

8. Tron address - `TFtY8yfRobcPkZ1yLZJh8AYAYMZdCRrSHQ`
