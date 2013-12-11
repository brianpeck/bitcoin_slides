% Bitcoin
% Brian Peck
% December 13, 2013

# What is Bitcoin?

## Cryptocurrency
> - Currency
> - Peer-to-peer payment network
> - Buy and sell things

------

![Bitcoin price over 6 months](images/bitcoin_charts.png)

# How to use Bitcoin?

## Wallet
> - May contains multiple addresses
> - Address is public 'key' to your account

------

![Public: 1vraci7fTMFqaHz3DGkpUQEBmMVRvNaGs](images/qr.png)

Key: 5KPgEXqb7FGSgCSF9iZhGHHzAFPFXzfg2uhA8rN7kS4Pt3UJhFA

## Sending Money
> - Send money to someone's public address
> - Verify with your private key

# Cryptography Primer

## Public Key Cryptography
> - Pairs of keys: Private (sign) and Public (verify)
> - Chosen together with various mathematical properties

---------
<!--Image credit: https://www.switch.ch/export/sites/default/uni/projects/grid/download_repository/crypto3.png-->

![Public Key Signing](images/crypto3.png)

## Cryptographic Hash Function
> - One-way function (hard to reverse)
> - Input: Arbitrary Block of Data
> - Output: Fixed-size bit string

# How it works

## Block Chain
> - Log of every transaction
> - Publicly available [(blockchain.info)](http://www.blockchain.info)

## Making a Transaction
> - X creates message "X pays Y 5 BTC"; signs it with private key
> - X broadcasts message to peer-to-peer network
> - Y can see transaction, verify that X sent it, and has the money
> - Unverified transaction - needs to be added to block chain

## Verifying a block
> - 'Miners' independently verify all network transactions
> - `hash("block"nonce) = XXXXXXX`
> - Maintains network integrity

# Okay, so what?

## Enable Micro transactions

## UX Design
