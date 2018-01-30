### Threat Models

To defend yourself, you need to know what you're defending against. There's multiple different threats to worry about, so let's divide them into common threats that you are likely to encounter and major threats that are rare but catastrophic.

Common Threats: Malware, forgetting instructions, improper key handling (i.e. giving a third-party site your private key), spoofing attacks (hackers creating fake websites), spoofed devices (e.g. ordering a Ledger off amazon and having the phrase already pre-set by an attacker)

Major Threats: fire, flood, burglary, file/hardware corruption

Figure out what you are most afraid of, and then design your wallet setup to ward off those fears.

As we increase the difficulty level, we are able to handle more and more of these threats. For example, the Gnosis Multi-Sig Wallet protects against the possibility of you losing one of your private keys by having a policy of "key redundancy". If you have a valid key, you are allowed to withdraw a certain amount of funds from the wallet (based on a pre-specified "daily withdrawal" limit).

However, the higher difficulty levels are still vulnerable to threats of their own, such as forgetting instructions.

If you chose a higher-level setup but put all your keys in the same location (thereby making the keys vulnerable to fire, flood, and burglary) or didn't make physical backups of your keys (thereby making the keys vulnerable to file/hardware corruption), than basically choosing that level is almost meaningless. You have to be prepared for a variety of different threats.