# What is An Ethereum Wallet?

Ethereum wallets are simply accounts on Ethereum that are not "smart contracts".

Every account has a public address (where ether can be sent to), and a private key (that only we have/control and see). The address can be derived from the private key. The private key is what is used for signing Ethereum transactions.

You cannot send an Ethereum transaction from an address without having the single private key to that address. If an attacker gets the private key, they can now be the signer of that account and can use and control the account forever.

Remember, funds are not sent to the private key, but to the public ethereum address - not to be confused with the public key. I know the wording is confusing.

## Using Seed Phrases To Create Accounts

Some accounts are created using Bip seed phrases - special kinds of phrases that can generate private keys. The tool I recommend generates a type of Bip phrase called a Bip39 seed phrase.

You can think of Bip39 seed phrases like this:

```
seed + password + HD Path => private key
private key => public key
public key => public address
```

A single Bip39 24 word seed phrase with a Bip39 password, along a particular path (called an HD path) will produce a particular private key.

That private key will then produce a public key.

*That* public key will then produce the public address.

Here's an example of a 24 word Bip39 seed phrase [fix with real phrase]:

	worth useful retire sausage worry 
	year wave sausage year used useful 
	sausage thank year wave satisfy team 
	hockey worth useful retire sausage wave

Using this password:

	fJF*(SDF*(*@J!)(SU*(D*F&^&TYSDFHL#@HO*&O

And this HD path:

	m/44'/60'/0'/0/0

We will derive this Ethereum private key:

	0xa7543cc9a372f2394cf4713ea8d6a8babf41c51f4fa964ff898420b333351fb1

Which will then derive to this Ethereum public key:

	0x033af70a7e5afa7f9a1eb98dc98b850b4100608bb5ba22d84e83946d5335ab4274

Which will derive to this public Ethereum address:
		
		0x3B741fdf155df3B0eE42f91D67390F6539f175aB

(Do not use this account for any real funds...you will lose everything you put in there.)

In order to steal the funds out of a wallet, someone needs to know the Bip39 seed phrase, and the password. Then they can just guess all the various HD paths (there are not that many options) until they get the private key.

Once they have the private key, then and only then can they attempt to take all the funds within the wallet.





Also note, the hex prefix “0x” is not included in the Bip39 tool’s private and public keys. It should always be added when handling addresses or private keys, if not presented. While it is a minor matter of formatting and is usually not a problem...it is good practice to add it if you don't see it.