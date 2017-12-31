### Level 1

- Basic Hardware Wallet
 1. Setup a single Ledger S Nano.
 2. Safely backup and record seeds.

- Basic Software Wallet with MyEtherWallet
 1. Download/Setup Tails 3.0 OS on a USB.
 2. Download/unzip/copy MyEtherWallet (MEW) onto a fresh SD card
 3. Shutdown/boot into Tails OS on USB
 4. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”
 5. Copy MEW off the SD Card into the “Tor Browser” folder, open the dist folder
 6. Unplug SD card
 7. Right-click `index.html` -> “Open with Tor Browser”
 8. Enter a strong passphrase, save the wallet file in Tor Browser folder, restore wallet with passphrase to get the address, record the address in a text document.
 9. Plugin SD card, copy the address text file and wallet backup onto SD card, shutdown Tails.

- Basic Software Wallet with Ian Coleman’s Bip39 Tool
 1. Download/Setup Tails 3.0 OS on a USB.
 2. Download/unzip/copy Ian Coleman's Bip39 Tool onto a fresh SD card.
 3. Shutdown/boot into Tails OS on USB.
 4. Click “+ (plus sign) -> Network Settings -> Disable All Network Connections -> Add -> Start Tails”.
 5. Copy the Bip39 Tool off SD Card into the “Tor Browser” folder, right-click the html file “Open With Tor Browser”.
 6. Unmount/Unplug SD card.
 7. Select “Supply your own source of entropy” and then input very strong entropy.
 8. Generate your Bip39 passphrase with KeePassX.
 9. Safely record and backup your seed and passphrase.
  <ul><li>I do not recommend recording on flash memory or SD, but if you do, make sure to encrypt this data before plugging in and saving on SD card.</li></ul>
 10. Copy first 5 addresses to a text document.
 11. Plug in SD card, copy the text document onto the SD card, and then unplug SD card.
 12. Shutdown and then reboot into Tails Offline.
 13. Plug in the SD card, copy Bip39 tool off SD card into Tor Browser folder, and then right-click html file “Open with Tor Browser”.
 14. Re-enter your recorded bip39 seed and passphrase, check the addresses generated are the ones you recorded
