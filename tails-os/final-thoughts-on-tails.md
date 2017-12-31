### Final Thoughts on Tails

#### Notes On Using Tails
- Tails can be run statelessly and without networking. This mode is great for offline transaction signing and account handling or creation.
- In order to run JS enabled apps or webpages offline, you must copy them into the “Tor Browser” folder in Tails. From there you can right click and run in Tails.
- Tails also comes with tools for verifying file hashes (e.g. MD5 hashes), safe browsing, and in stateless mode cannot be written to permanently. This is handy for handing crypto tools and files.

### Notes on Tails Security
- Remember, Tails is designed for privacy, not necessarily for complete security. They are synergistic and often go hand in hand, though.
- My biggest worry with Tails is the secure download of Tails itself. By using BitTorrent you can be assured that you will get the right ISO that the website wants you to download, but if the site was hacked, it’s up to the community to figure out if the BitTorrent link/download is accurate and somehow warn you. Given the Tails community though, this seems highly unlikely to happen by a hacker to their site.
- State-level actors could certainly intervene on the connection, and replace out the file or link altogether, but it becomes more and more complicated to actually verify the download and if a man-in-the-middle attack was activated on you. At that point, you literally have to rely on the developers of Tails or the Tor/Tails community directly to help verify your ISO. However, my main concern is not state-level actors. I am more focused on hackers trying to steal funds or break things.
- Please read [the Tails warning](https://tails.boum.org/doc/about/warning/index.en.html). Tails is not designed to cover everything. It is just generally safer and less leaky that most modern OSes.