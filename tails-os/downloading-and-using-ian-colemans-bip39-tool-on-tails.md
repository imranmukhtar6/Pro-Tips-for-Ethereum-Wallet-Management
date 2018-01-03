### Downloading and Validating Ian Coleman's Bip39 Tool on Tails

#### Downloading and Using
1. Go to https://iancoleman.github.io/bip39/

2. Right-click, “Save as…”

3. Select “Webpage [Complete]..”

4. Save the Webpage on to a SD card.

5. Boot into Tails Offline.

6. Select “Places” (top right on screen) → “Tor Browser”.

7. Copy the .html file off the SD card into the “Tor 
Browser” folder.

8. In the Tor Browser Folder, right click the file and “Open with Tor Browser”.

### Validating Ian Coleman’s Bip39 Tool
1. Go to Ian Coleman's Bip39 tool's Github page (link: https://github.com/iancoleman/bip39/releases).

2. Go to releases and then download the latest version's .html file<sup>1</sup>.

3. In Linux or Tails, `cd ./path/to/bip39-standalone.html` then run `sha256sum ./bip39-standalone.html`.

4. Compare the result with the one listed on the release in Github.

5. Compare the result with the tweet on twitter by Ian Coleman: `https://twitter.com/bip39tool`

6. If all hashes match up, you have the right file.

7. (Optional) On a phone or separate connection, check to see if the Github hash and Twitter hash all are the same. Having multiple points of reference from multiple connections are a way to validate the tools integrity (GPG and Bittorrent are also good methods if available).

**Footnotes**

1 - The first section (Downloading and Using) states that you should download straight from the website, while the second section (Validating) states that you should download from the Github page. Which advice should we prefer? Or should we download from multiple sources, in case one of them gets compromised?