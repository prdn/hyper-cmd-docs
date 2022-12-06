### Peer-host resolution

Hypertele supports peer resolution, allowing to map mnemonic names (.ie myserver) with a peer public key. Search priority is `.`, `~/`, `/etc/` `/Users`.

```
example: ~/.hyper-hosts

myserver PEER_KEY_0
workserver PEER_KEY_1
```
