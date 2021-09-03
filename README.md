Wrecksas
--------

This Chromium extension prefills the pro-life whistleblower form with garbage data.
You still have to hit the reCAPTCHA button and submit.  When done, hit refresh, and it'll be filled with new garbage.

## Installation

* Clone this repo to your machine, or download it as a zip and extract somewhere.
* in Chrome/Chromium, go to `chrome://extensions`
* flip on "Developer mode" in the upper right-hand corner
* click "Load unpacked"
* Browse to this folder.

## Modifying

If you add or remove files within `./src`, run `node ./remanifest.js` to make sure `manifest.json` is kept up-to-date, otherwise, you'll get script permission errors.
