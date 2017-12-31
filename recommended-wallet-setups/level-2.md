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
 3. Setup an Offline Air-Gapped Computer.
 4. Shutdown/boot into Tails OS on USB on the Offline Air-Gapped Computer.
 5. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”
 6. Copy MEW off the SD Card into the “Tor Browser” folder, open the dist folder
 7. Unplug SD card.
 8. Right-click `index.html` -> “Open with Tor Browser”.
 9. Enter a strong passphrase, save the wallet file in the Tor Browser folder, restore wallet with passphrase to get the address, and record the address in a text document.
 10. Shutdown the Tor Browser.
 11. Plug in the SD card and copy the address text file and wallet backup onto the SD card.
 12. Shutdown Tails.
 
- Basic Offline Air-Gapped Software Wallet with Ian Coleman’s Bip39 Tool
  1. Download/Setup Tails 3.0 OS on a USB.
  2. Download/unzip/copy Ian Coleman's Bip39 Tool onto a fresh SD card.
 3. Setup an Offline Air-Gapped Computer.
 4. Shutdown/boot into Tails OS on USB on Air-Gapped Offline Computer.
 5. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”
- Copy the Bip39 Tool off SD Card into the “Tor Browser” folder, right-click the html file “Open With Tor Browser”.
 6. Unmount/Unplug the SD card.
 7. Select “Supply your own source of entropy”, input very strong entropy.
 8. Generate your Bip39 passphrase with KeePassX.
 9. Safely record and backup your seed and passphrase.
<ul><li>I do not recommend recording on flash memory or SD, but if you do, make sure to encrypt this data before plugging in and saving on SD card.</li></ul>
 10. Copy first 5 addressed to a text document.
 11. Plug in SD card, copy the text document onto the SD card, and then unplug SD card.
 12. Shutdown and then reboot into Tails Offline.
 13. Plug in the SD card, copy Bip39 tool off SD card into Tor Browser folder, and then right-click html file “Open with Tor Browser”.
 14. Re-enter your recorded bip39 seed and passphrase, check the addresses generated are the ones you recorded
