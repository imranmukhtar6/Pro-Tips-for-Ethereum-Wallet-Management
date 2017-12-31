### Level 3

- 3 of 5 Gnosis Multi-Signature Wallet
- Setup/boot your Air-Gapped Offline Computer
- Boot Tails OS via USB on your Offline Computer
- Setup 5, Level 2, software or hardware wallets, record 5 account addresses
- Open https://wallet.gnosis.pm/ in a secured browser
- Use your Ledger S Nano to activate the wallet dApp
- Select “new”
- Specify your 5 account addresses as the wallet owners
- Specify a daily limit (keep it reasonable)
- Deploy the Wallet contract
- Test a small `submitTransaction` transaction withdrawal with all 5 accounts
- Once all accounts successfully have withdrawn a small amount of funds from the wallet
- Deposit an amount slightly larger than the Daily Limit
- Attempt a 3 signature withdrawal from the multi-signature wallet
- Now you can use that multi-signature wallet as your cold-store wallet
