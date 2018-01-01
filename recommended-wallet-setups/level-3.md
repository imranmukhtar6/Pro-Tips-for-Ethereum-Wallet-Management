### Level 3

- 3 of 5 Gnosis Multi-Signature Wallet, Using an "Online Computer" (that is a computer that *is* connected to the Internet)
 1. Boot Tails OS via USB on your Normal Online Computer
 2. Setup 5 *Level 1* software or hardware wallets. Record those 5 account addresses offline.
 3. Boot Online Computer
 4. Open https://wallet.gnosis.pm in a secured browser
 5. Use your Ledger Nano S or MetaMask to activate the wallet dApp.
 6. Select “new”.
 7. Specify your 5 account addresses as the owners of the wallet.
 8. Specify a daily limit. Keep it reasonable.
 9. Deploy the Wallet contract.
 10. Test a small `submitTransaction` transaction withdrawal with all 5 accounts, with the destination set to the account used.
 <ul>
  <li>By following this withdrawal process, hackers can see that you have potentially read this article and are following these instructions.</li>
 </ul>
 11. Once all accounts successfully have withdrawn a small amount of funds from the wallet, deposit an amount slightly larger than the Daily Limit.
 12. Attempt a 3-signature withdrawal from the multi-signature wallet
 13. Now you can use that multi-signature wallet as your cold-store wallet.