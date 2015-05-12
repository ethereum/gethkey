# gethkey

This is a temporarily solution to extract private keys from the old key store on the current olympic test net. This will only work for clients that have old keys (geth <v0.9.20).

Usage:

`gethkey <address> <export_file>`

Installation:

Installation assumes you have [godep](https://github.com/tools/godep) installed

```
git clone https://github.com/ethereum/gethkey.git
cd gethkey
godep go install
```
