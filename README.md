# js_deobfuscator

PoC js deobfuscator for custom obfuscator for [this file](https://vidstream.pro/assets/vidstream/cache/scripts.js?61678c87). It's PoC so code is pretty messy and there is a lot of false positives but deobfuscated code is still readable.

To run deobfuscator, first use any JS beautifier on obfuscated code, save it to `script.js` and then run:

`node deoubfuscator.js`

It will deobfuscate script from `script.js` and store deobfuscated version in `deob_script.js`
