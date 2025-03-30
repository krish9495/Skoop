# Skoop: Decentralized News Platform 📰

Skoop is a decentralized news platform built on the Ethereum blockchain. It allows users to access news articles securely and transparently without relying on a centralized authority.

## Features 🌟

- Decentralized news publishing and verification
- Blockchain-based content verification
- User authentication via MetaMask
- News categorization (National, Political, Business, Sports)
- Real-time news updates
- Community-driven content moderation

## Tech Stack 🛠️

- Frontend: React.js, Vite, TailwindCSS
- Blockchain: Solidity, Hardhat
- Smart Contract Platform: Ethereum (Sepolia Testnet)
- Web3 Integration: ethers.js

## Live Demo 🚀

[View Live Demo](https://skoops.vercel.app)

## Smart Contract Address 📝

Sepolia Testnet: `0xc3cCab5689A162D1c4C35bBCd15B56E7Ccab7A85`

## Setup Locally 🛠️

### Prerequisites
- Node.js installed on your machine
- MetaMask extension installed in your browser
- Solidity development environment (e.g., Hardhat)
- Some Sepolia testnet ETH

### Clone the Repository
```bash
git clone https://github.com/sushilpandeyy/skoop.git
cd skoop
```

### Install Dependencies

#### Client (Frontend) 💻
```bash
cd client
npm install
```

#### Smart Contract (Blockchain) ⛓️
```bash
cd ../SmartContract
npm install
```

### Run the Application

#### Client (Frontend) 💼
```bash
cd client
npm run dev
```

#### Smart Contract (Blockchain) ⚙️
No need to redeploy as the contracts are already deployed on the Sepolia testnet.

## Deployment 🚀

### Frontend Deployment (Vercel)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Deploy with default settings

### Smart Contract Deployment
1. Set up environment variables in `.env`:
   ```
   SEPOLIA_URL=your_sepolia_rpc_url
   PRIVATE_KEY=your_wallet_private_key
   ```
2. Deploy using Hardhat:
   ```bash
   npx hardhat run scripts/deploy.js --network sepolia
   ```

## Contributing 🤝

Feel free to contribute to the Skoop project by creating issues or submitting pull requests.

## License 📝

This project is unlicensed. Feel free to use it as you please!

# Fake News Detector Model

This repository contains a machine learning model for detecting fake news. The model is designed to assess the quality of news articles before they are deployed on a blockchain platform.

## Model Files

Due to the large size of the model file, it's hosted on OneDrive. You can download the model from the following link:

[Click here to access the Fake News Detector model](https://drive.google.com/drive/folders/1OAJMFrJ2_JXa96CB7ZfWDOHpzdHq867C?usp=sharing)

## Dependencies

To use the model, you'll need to install the following dependencies:

- PyTorch
- TensorFlow
- NumPy
- Pandas
- Transformers

You can install them using pip:

```bash
pip install torch tensorflow numpy pandas transformers
```

## Usage

After installing the dependencies, you can use the provided sample code to load and utilize the model for fake news detection.

### Accessing the Platform 🚀

- Once the contracts are deployed and the frontend server is running, open your browser and navigate to the URL where the frontend is hosted (usually `http://localhost:5173`).
- Connect your Metamask wallet to the Sepolia testnet.
- Use the platform to access news articles. Note that adding as a user might require spending some test Ether.
