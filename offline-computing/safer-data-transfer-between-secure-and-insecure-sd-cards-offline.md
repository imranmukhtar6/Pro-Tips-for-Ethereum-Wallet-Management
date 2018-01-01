### Safer Data Transfer Between Secure and Insecure SD Cards Offline

You may want to transfer data between sensitive and nonsensitive SD cards. This should be done through Tails, preferably with encryption. Here is a quick process flow for doing a safe transfer.

Note that this does not protect against SD card reader malware. It is purely just to create some distance between cards that will touch your Air-Gapped machine and your online day-to-day computer.

In general, you just want to copy data once from your online machines. Creating any passing of data off and on from the air-gapped machine must be done with great caution<sup>1</sup>.

#### Transfer Steps:
1. Plug In fresh SD card to online computer.
2. Copy tools/data/files onto the SD card.
3. Plug in Tails USB, boot into Tails Offline
4. Copy tools/data/files off the insecure SD card onto the Desktop or Home folder.
5. Unplug the insecure SD card.
6. Plugin the sensitive SD card.
7. Safely transfer files onto the secure SD card.
8. Plug in SD card to Air-Gapped machine.

### Footnotes
1 - It is unclear what this sentence means.