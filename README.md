## Hi there 👋
- 🔭 I’m currently working on creating a Website meant for all tesla products sales including it cars solar n batteries n all of em

## Setup Instructions

1. Install Node.js and npm if not already installed:
   ```
   apt update && apt install -y nodejs npm
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set environment variables (create .env.local):
   ```
   NEXTAUTH_SECRET=your-secret
   NEXTAUTH_URL=http://localhost:3000
   EMAIL_USER=your-email@gmail.com
   EMAIL_PASS=your-app-password
   ```

4. Run the development server:
   ```
   npm run dev
   ```

5. Open http://localhost:3000 in your browser.

## Features Added

- Shopping cart with localStorage persistence
- User authentication with NextAuth
- Bitcoin payments using QR code to your wallet address: 3LMNDZLK2TkHDCCeBPhzfEA1qBVHSHjVTk
- Email order confirmations (requires Gmail app password)
- Payment verification via BlockCypher API

Note: This is a demo. In production, use a database for users and orders, secure env vars, and monitor Bitcoin transactions.