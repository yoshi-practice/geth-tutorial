# Geth Tutorial
This is geth (go and Ethereum)tutorial repository.

---

## Geth install

```
$ brew tap ethereum/ethereum
$ brew install ethereum
```

## Make directory

```
$ mkdir ~/eth_test | cd eth_test | pwd
/Users/home/eth_testnet
```

## Create genesis.json

```
$ vim genesis.json
```

## Initialize `genesis.json`

```
$ geth --datadir ~/eth_test init ~/eth_test/genesis.json
```

## Run Geth

```
$ geth --networkid 4649 --nodiscover --maxpeers 0 --datadir ~/eth_test console 2>> ~/eth_test/geth.log
```
