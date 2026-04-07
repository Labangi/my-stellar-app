# GeoAlert - Decentralized Geo-based Alert System

GeoAlert is a decentralized application (dApp) built on **Stellar Soroban** that enables users to create, manage, and respond to location-based alerts on-chain.

## 🚀 Features

- 🌍 **Geo-based Alerts**: Create alerts with latitude, longitude, and radius
- ⚠️ **Severity Levels**: Alerts support severity from 0–5 with escalation
- 🔔 **Alert Lifecycle**: Create → Acknowledge → Escalate → Resolve
- 👥 **Multi-user Interaction**: Different users can respond to alerts
- ⏱️ **Expiration Support**: Alerts expire based on timestamp
- 🔗 **Fully On-chain**: All data stored and managed via Soroban smart contract
- 💰 **Wallet Integration**: Uses Freighter wallet for Stellar network interaction

## 🛠️ Tech Stack

- **Frontend**: React 19 + Vite
- **Blockchain**: Stellar Soroban (Rust smart contract)
- **Wallet**: Freighter API
- **SDK**: Stellar SDK for JavaScript

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd my-stellar-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Install Rust and Soroban CLI for contract development (optional):
   - Follow [Soroban setup guide](https://soroban.stellar.org/docs/getting-started/setup)

## 🚀 Usage

1. Start the development server:
   ```bash
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:5173`

3. Connect your Freighter wallet

4. Create and manage geo-based alerts

## 🏗️ Smart Contract

The smart contract is located in `contract/contracts/hello-world/`.

### Build the contract:
```bash
cd contract
make build
```

### Deploy to testnet:
```bash
make deploy
```

Update the `CONTRACT_ID` in `lib/stellar.js` with the deployed contract ID.

## 📸 Screenshots

![GeoAlert UI](public/Screenshot%202026-04-01%20004735.png)
![Alert Management](public/Screenshot%202026-04-01%20004828.png)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License
This project is licensed under the MIT License.


## Contract Address
https://stellar.expert/explorer/testnet/contract/CDSDNMSPRCOVYZKIHDAWOGUGT5IN4RETJV6FBGZQMXTHRMFMUGCDT7CX
