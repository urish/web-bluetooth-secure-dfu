nRF5x Secure DFU using Web Bluetooth

Copyright (C) 2017, Uri Shaked. License: MIT.

[Online version](https://urish.github.io/web-bluetooth-secure-dfu)

## About

This is a proof of concept for updating Nordic nRF5x-based solutions over the air, using their Secure DFU process.

The core functionality is implemented as a [plain ES2017 class](secure-dfu.js), so it works out of the box on Chrome 55+ / Node 7.5.0, while older versions / different browsers require transpilation to either ES2015 or ES5. But no other browsers currently support Web Bluetooth, so it shouldn't be a big issue anyway.
