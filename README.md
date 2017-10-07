BlocknetDX repository



Step 2.

Step 3.
Initiator creates TxAb. TxAb can be redeemed after time T2 with privkey i1. At any time TxAb can redeemed with signature from privkey r1 and reveal of secret X. Initiator broadcasts TxAb onto the network.

Step 4.
Responder confirms TxAb. Responder creates TxBb. TxBb can be redeemed after T1 time with privkey r2. At any time TxBb can be redeemed with signature fom privkey i2 and reveal of secret X. Responder broadcasts TxBb onto the network.

Step 5.
Initiator creates TxBp which spends TxBb using privkey i2 and secret X. With the revealed secret, responder can create TxAp which spends TxAb with privkey r1 and secret X.
```
