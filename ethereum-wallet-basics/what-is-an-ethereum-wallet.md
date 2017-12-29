# What is An Ethereum Wallet?

Ethereum wallets are simply accounts on Ethereum that are not "smart contracts".

Every account has a public address (where ether can be sent to), a public key, and a private key (that only we have/control and see). The address can be derived from the public key and the public key can be derived from the private key. The private key is what is used for signing Ethereum transactions.

You cannot send an Ethereum transaction from an address without having the single private key to that address. If an attacker gets the private key, they can now be the signer of that account and can use and control the account forever.

Remember, funds are not sent to the private key, but to the public ethereum address - not to be confused with the public key. I know the wording is confusing.