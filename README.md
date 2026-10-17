# W3C Pi Token Metadata

This repository hosts the public metadata files for the **W3C** test token created by W3C Digital Network for use on **Pi Testnet**.

The metadata helps compatible wallets and services identify the token and display its name, token code, issuer address, decimal precision, description, and icon.

## Token Details

- **Token name:** W3C PI Bookings
- **Token code:** W3C
- **Network:** Pi Testnet
- **Purpose:** Test token associated with the W3C PI Bookings project
- **Issuer:** `GCIPTMBGZ2IXATBZPZTLQYT7OLUC7IJTDBKTFIUAFM4A35R6UU5BLN3W`
- **Display precision:** 7 decimal places

This is a **testnet token**, not a claim that the token has mainnet status or market value.

## Metadata Files

- [Pi token metadata](.well-known/pi.toml) — token information formatted for Pi-compatible services.
- [Stellar-style token metadata](.well-known/stellar.toml) — equivalent currency information in Stellar TOML format.
- [Metadata landing page](index.html) — a simple page linking to the metadata files.

## Live Metadata

When this repository is deployed with its current configuration, the files are intended to be available at:

- `/.well-known/pi.toml`
- `/.well-known/stellar.toml`

The hosting configuration serves these TOML files as plain text and allows cross-origin access for compatible clients.

## Project

W3C Digital Network builds digital services and projects. Learn more at [web3currency.online](https://web3currency.online).

---

Metadata describes the token for identification and display purposes; it does not by itself create, issue, or verify a token on the network.
