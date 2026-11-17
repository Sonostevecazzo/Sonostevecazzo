# PrenotaAI

Mobile-first web application for assisted CUP queue waiting. This repository is public by explicit owner authorization.

## Intended demo configuration

- Demo mode only (`PHONE_PROVIDER=mock`).
- Real calls disabled (`ENABLE_REAL_CALLS=false`).
- No automatic medical booking; the citizen speaks directly with the CUP operator.
- Do not commit credentials, `.env` files, phone numbers, health data, or production secrets.

## Project status

The queue-position detector is designed to trigger a callback at announced queue position 2 or 1. The real telephony audio/STT integration and authorized CUP field validation are not complete. This project is not approved for real-world healthcare use.

The repository has been initialized, but the application source and hosting deployment have not yet been transferred/configured.
