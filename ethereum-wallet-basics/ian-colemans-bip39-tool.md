## Ian Coleman's Bip39 Tool

Ian Coleman is a cryptocurrency expert and developer who has made an awesome Bip39 utility. The tool allows you to generate and recover Bip39 seed phrases and derive Ethereum account key pairs from it. The tool is well tested, and simple by design.

It also has:
- Support for Bip32 settings, allowing you specify unique HD paths.
- Good use of clear, reliable and safe system entropy generation that is to be paired with user inserted entropy.
  - Entropy is just another word for randomness, and the more randomness you have, the harder it will be for someone to guess your seed or password.

If we know the password and our Bip39 seed phrase, we can  recover our private key with Ian Coleman's tool. Let's try it out with the example password and Bip39 seed phrase we used in the last chapter.

The Bip39 seed phrase is [replace with actual phrase]:

    worth useful retire sausage worry
    year wave sausage year used useful
    sausage thank year wave satisfy team
    hockey worth useful retire sausage wave

And the password is:

    fJF*(SDF*(*@J!)(SU*(D*F&^&TYSDFHL#@HO*&O

1. Go to https://iancoleman.io/bip39/
2. Enter the Bip39 seed phrase and the password.
3. Set “Coin” to “Ethereum”.
4. Scroll down. You will see the first address is the one above. Scroll over and the first private key is the one above. [The instructions need to be rewritten once an actual Bip39 seed phrase is generated.]