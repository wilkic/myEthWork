# myEthWork
notes on getting up and running with ethereum

https://www.ethereum.org/

## Get Geth
1. https://ethereum.org/cli
1. Learn
  * https://github.com/ethereum/go-ethereum/wiki/Contracts-and-Transactions
1. Setting up dev env (also detailed on https://ethereum.org/cli but this kinda spelled it out more, and gave an example genesis.json file)
  * http://hidskes.com/blog/2015/08/12/creating-a-testnet-using-geth/
   * Note had to `mkdir '~/.ethereum/DevChain'`
```
$ geth --rpc --networkid=39318 --maxpeers=0 --datadir=~/.ethereum/DevChain/ --mine --minerthreads 1 --genesis genesis.json console
```
   * Except that didn't work because i had no acct, so left out the '--mine' and it started up:
```
$ geth --rpc --networkid=39318 --maxpeers=0 --datadir=~/.ethereum/DevChain/  --minerthreads 1 --genesis genesis.json console
```

## Get Solidity
1. https://solidity.readthedocs.org/en/latest/
1. https://solidity.readthedocs.org/en/latest/installing-solidity.html#binary-packages
1. Browser based solidity
  * https://chriseth.github.io/browser-solidity/

## hello world
1. https://ethereum.org/greeter


