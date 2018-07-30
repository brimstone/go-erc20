ERC20
=====

This is a package for the ERC20 ABI (Application Binary Interface) for Ethereum
tokens.

This was written because I couldn't find one readily available.

Usage
-----

```go
tokenInstance, err := ERC20.NewERC20(contractAddress, clientInstance)

symbol, err := tokenInstance.Symbol(nil)

balance, err := tokenInstance.BalanceOf(nil, accountAddress)
```

This is just an example, but there's a bunch of methods to an ERC20 token.

Resources
---------

I found the following resource helpful:
- https://goethereumbook.org/smart-contract-read/
