# PrenotaAI

Mobile-first web application for assisted CUP queue waiting. This repository is public by explicit owner authorization.

## Current deployment profile

- Demo mode only (`PHONE_PROVIDER=mock`).
- Real calls disabled (`ENABLE_REAL_CALLS=false`).
- No automatic medical booking; the citizen speaks directly with the CUP operator.
- Do not add credentials, `.env` files, phone numbers, health data, or production secrets to this repository.

The application source is packaged in `prenotaai-0.4.2-mobile-pwa.zip`. Render deployment configuration is in `render.yaml`.

## Status

The queue-position detector is designed to trigger the callback at announced queue position 2 or 1. The real telephony audio/STT integration and authorized CUP field validation are not yet complete. This is not approved for real-world healthcare use.
