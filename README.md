# TTLock API Documentation

Reference documentation for the [TTLock](https://open.ttlock.com/) Cloud API, maintained by ISL Technologies for use across the ISLKey access-control platform.

## Contents

| File | Description |
| --- | --- |
| [`API Error Codes`](./API%20Error%20Codes) | Consolidated list of TTLock Cloud API error codes and their descriptions, grouped by category. |

## API Error Codes

The `API Error Codes` file catalogues the numeric error codes returned by the TTLock Cloud API, organised into sections such as:

- **Account, rights and common errors** — authentication, token, and rate-limit failures (e.g. `10000` client not found, `10003` token does not exist, `30006` exceeds API call limit).
- **Lock related errors** — lock lifecycle and capability errors (e.g. `-1003` lock does not exist, `-2025` frozen lock).
- **eKey related errors** — eKey issuing and permission errors (e.g. `-1008` eKey does not exist, `-2019` cannot send an eKey to yourself).

Use it as a quick lookup when integrating against the TTLock OAuth 2.0 / Cloud API and handling error responses.

## Related projects

- **ISLKey** — access-control platform that integrates with TTLock locks.
- **Flutter-App** — cross-platform smart-lock control app built on the TTLock SDK.

## Notes

This repository is documentation only; it contains no runnable code. The error codes are reproduced for developer reference and may change as TTLock updates its API — always cross-check against the [official TTLock developer portal](https://open.ttlock.com/).
