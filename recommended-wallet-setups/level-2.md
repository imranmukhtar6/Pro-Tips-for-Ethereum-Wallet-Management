### Level 2

- Complex Hardware Wallet (Air-Gapped Setup with Bip39 Passphrase)
 1. Setup a single Ledger Nano S. Plug into a plug not computer when creating seed/accounts.
 2. Upgrade/verify that your Ledger Nano S is at version 1.3.1.
 3. Enable Shuffle Pin and set the Timeout.
 4. Enable Pin with Bip39 Passphrase (generate passphrase offline with KeePassX).
 5. Backup and encrypt passphrase with KeePassX database on SD Card.
 6. Safely backup and record your seed, passphrase and accounts.
 7. Reset the Ledger S Nano wallet device.
 8. Restore the reset device to the seed and passphrase you recorded.
 9. Verify the accounts you recorded are the same as the ones from the newly restored hardware wallet.
 
- Basic Offline Air-Gapped Software Wallet with MyEtherWallet
 1. Download/Setup Tails 3.0 OS on a USB.
 2. Download/unzip/copy MyEtherWallet (MEW) onto a fresh SD card.
 3. Setup an Air-Gapped Offline Computer.
 4. Shutdown/boot into Tails OS on USB on the Air-Gapped Offline Computer.
 5. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”
 6. Copy MEW off the SD Card into the “Tor Browser” folder, open the dist folder
 7. Unplug SD card.
 8. Right-click `index.html` -> “Open with Tor Browser”.
 9. Enter a strong passphrase, save the wallet file in the Tor Browser folder, restore wallet with passphrase to get the address, and record the address in a text document.
 10. Shutdown the Tor Browser.
 11. Plug in the SD card and copy the address text file and wallet backup onto the SD card.
 12. Shutdown tTails.
