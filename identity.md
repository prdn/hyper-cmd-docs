## Identity

### Usage

Install toolbox

```sh
npm install -g hyper-cmd-utils
```

Generate a seed (ie. for hypertele server, ...)

```sh
hyper-cmd-util-keygen --gen_seed
```

Generate a keypair (ie. for hypertele client, hyperssh, ...)

```sh
hyper-cmd-util-keygen --gen_keypair mykeypair.json
```

### Identity resolution

Hypertele supports identity resolution for clients.
Search priority is `.`, `~/`, `/etc/` `/Users`.

```
example: ~/.hyper-id.json

{"secretKey":"ad2c134532cf6ea88e945993d5779f61c386911842e985d4bdd1f0f8d1e332d78ae76d1d5243ac80c5acb3d39b04c81782802ac1f75b30c6b249ec59c762a077","publicKey":"8ae76d1d5243ac80c5acb3d39b04c81782802ac1f75b30c6b249ec59c762a077"}
```
