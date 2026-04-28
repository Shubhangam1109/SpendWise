<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run SpendWise with backend auth

This repo contains a React Native Web SpendWise app plus a local auth backend (email/password and social OAuth).

## Run Locally

**Prerequisites:** Node.js

1. Install dependencies:
   `npm install`
2. Copy `.env.example` to `.env.local` and configure values.
3. Start the auth backend:
   `npm run auth:server`
4. In a second terminal, start the app:
   `npm run dev`
