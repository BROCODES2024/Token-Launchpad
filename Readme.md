# Token Launchpad App

## Overview

Token Launchpad is a Solana-based web application that allows users to create and mint their own SPL tokens using a simple UI.

## Features

- Connect a Solana wallet
- Create an SPL token with a name, symbol, image URL, and initial supply
- Mint tokens to an associated account
- Uses Solana Devnet for testing

## Tech Stack

- **React.js** (Frontend framework)
- **Solana Web3.js** (Solana blockchain interactions)
- **@solana/spl-token & @solana/spl-token-metadata** (Token and metadata operations)
- **Vite** (Build tool)

## Prerequisites

Ensure you have the following installed:

- Node.js (>= 16)
- Yarn or npm
- A Solana wallet (e.g., Phantom)

## Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/BROCODES2024/Token-Launchpad.git
   cd Token-Launchpad
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

   or

   ```bash
   yarn dev
   ```

4. Open the application in your browser:
   - The app should be running at `http://localhost:5173/` (or as shown in your terminal).

## How to Use

1. Connect your Solana wallet (Phantom recommended).
2. Enter the token details:
   - **Name** (e.g., "MyToken")
   - **Symbol** (e.g., "MTK")
   - **Image URL** (Metadata reference)
   - **Initial Supply**
3. Click **Create a Token**.
4. The app will create a new token and mint it to your associated account.

## Folder Structure

```
Token-Launchpad
├─ Readme.md
└─ Token-Lauchpad
   ├─ eslint.config.js
   ├─ index.html
   ├─ package.json
   ├─ public
   │  └─ vite.svg
   ├─ README.md
   ├─ src
   │  ├─ App.css
   │  ├─ App.jsx
   │  ├─ assets
   │  │  └─ react.svg
   │  ├─ components
   │  │  └─ TokenLaunchpad.jsx
   │  ├─ index.css
   │  └─ main.jsx
   └─ vite.config.js
```

## Deployment

To deploy the app using Vercel:

```bash
npm run build
vercel deploy
```

## Contact

For any issues, feel free to reach out or open an issue in the GitHub repository.

**GitHub Repository:** [Token Launchpad](https://github.com/BROCODES2024/Token-Launchpad.git)
