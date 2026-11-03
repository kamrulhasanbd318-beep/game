# KamrulPay

KamrulPay digital wallet project.

## Project package

Upload the provided `KamrulPay-my-wallet-app.zip` package to this repository, or extract it and upload the `my-wallet-app` folder contents.

## Important deployment notes

- Backend: Node.js / Express
- Database: MongoDB
- Configure environment variables using `.env.example`.
- Payment-provider webhooks are not enabled yet. Do not use this as a live-money wallet until official provider integration, signature verification, payout settlement, and end-to-end testing are completed.
- GitHub Pages can host static frontend files only; it cannot run the Express backend.
