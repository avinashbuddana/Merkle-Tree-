# Merkle Tree For Whitelist Users using node js and solidity (JavaScript)

<hr />

## Install npm packages

[`npm install merkletreejs`](https://www.npmjs.com/package/merkletreejs)

[`npm install keccak256`](https://www.npmjs.com/package/keccak256)

## Run program (root of repo)

`node merkle_tree.js`

Play around with this line:
`const claimingAddress = leafNodes[0];`
to see if an address is verified in the Merkle Tree or Not.

## Solidity Version

```json
    Pass this array in for 'bytes32[] calldata _merkleProof' to whitelistMint()

    👋 CHANGE SINGLE QUOTES TO DOUBLE QUOTES
        '0Xaddr' -> "0xaddr"

    [
        "0x702d0f86c1baf15ac2b8aae489113b59d27419b751fbf7da0ef0bae4688abc7a",
        "0xb159efe4c3ee94e91cc5740b9dbb26fc5ef48a14b53ad84d591d0eb3d65891ab"
    ]

```
My Medium blog on merkle tree
https://medium.com/@avinashbuddana4/merkel-tree-7c1e00e136b0
