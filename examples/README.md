# Binance API - Examples

This folder contains ready to go examples demonstrating various aspects of this API implementation, written in typescript.

Found something difficult to implement? Contribute to these examples and help others!

## Getting started

- Clone the project (or install the module in your own project `npm install binance`).
- Edit the sample as needed (some samples require edits, e.g APi keys or import statements).
- Execute the sample using ts-node: `ts-node examples/rest-spot-public.ts`.

Samples that API credentials using `process.env.APIKEY` can be spawned with environment variables. Unix/macOS example:
```
APIKEY="apikeypastedhere" APISECRET="apisecretpastedhere" ts-node examples/ws-userdata.ts
```
