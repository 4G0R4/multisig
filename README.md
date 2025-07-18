coinbin
=======

An Open Source Multisig Support Tool. Version 1.3 by 4G0R4.
Forked from https://github.com/real1510/multisig by real1510.

Original live version available at [https://multisig.btcnet.eu/](https://web.archive.org/web/20200508210414/https://multisig.btcnet.eu)

As the original Coinb.in, it supports a number of key features such as: 

- Offline Compressed & uncompressed Address creation.
- Offline Multisignature Address creation.
- "In browser" Key (re)generation. 
- Send and receive payments.
- Ability to decode transactions, redeem scripts and more offline.
- Build custom transactions offline.
- Sign transactions offline.
- Signatures are deterministic as per RFC 6979 (https://tools.ietf.org/html/rfc6979#section-3.2)
- Broadcast transactions.
- nLockTime support.
- Add custom data to transactions with the use of OP_RETURN.
- Support current Dark Wallet Stealth Address structure (as of version Alpha 7) for outputs.
- Brain wallet support.
- Compatible with bitcoin-qt
- An offical .onion address for tor users.
- Offline qrcode creator and scanning tool
- HD (bip32) support
- Supports altcoins such as litecoin
- Replace by fee (RBF) Support
- Segwit Support
- Bech32 address support
- Fee calculator - https://coinb.in/#fees

Changes:

- Remove wallet function and LocalBitcoins link.
- Use blockchain.info to load unspent transactions and to push transactions.
- Remove fee calculator.

