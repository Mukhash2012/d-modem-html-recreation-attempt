# D-Modem HTML Recreation Attempt

This repository contains a standalone `modem.html` implementation.

## Running

Open `modem.html` directly in a modern browser. There are no build steps, CDN dependencies, or external JavaScript files.

## Implemented standards

- Bell 103
- V.21
- V.23
- Bell 202
- V.22
- Bell 212A
- V.22bis
- V.32
- V.32bis
- V.34-style
- V.90-style
- V.92-style

V.32+ entries use independent browser-side handshake and dense-QAM signal models for demonstration and loopback work. They are not substitutes for the source repository's protocol-complete DSP implementations and should not be advertised as standards-certified interoperation.

The HTML implementation is experimental and is not licensed or certified by any modem standards body.
