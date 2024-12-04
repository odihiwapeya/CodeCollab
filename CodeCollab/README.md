# EcoTrack

EcoTrack is a blockchain-based application designed to track personal carbon footprints and reward users for environmentally friendly actions. Built on the Internet Computer platform, EcoTrack incentivizes users to reduce their carbon emissions by offering reward points based on their activities. The platform allows users to log their activities, calculate their carbon emissions, and earn rewards for reducing their environmental impact. The backend is built using Node.js, Express.js, and Azle, ensuring secure and persistent data storage with StableBTreeMap.

## Features
- Track personal carbon footprints
- Reward points for reducing carbon emissions
- Decentralized and secure data storage on the blockchain
- User-friendly API to interact with carbon footprint data
- Built with Node.js, Express.js, and Azle

## Installation

### Prerequisites
- Node.js (version 20 or later)
- DFX (Internet Computer SDK)

### Instructions:

1. **Clone the repository**:
   - Clone the repository to your local machine:
     ```bash
     git clone https://github.com/your-username/orgfund.git
     cd orgfund
     ```

2. **Install dependencies**:
   - Run the following command to install the necessary dependencies:
     ```bash
     npm install
     ```

3. **Start DFX**:
   - Start the local DFX environment:
     ```bash
     dfx start
     ```

4. **Deploy the canister**:
   - Deploy the canister to the Internet Computer network:
     ```bash
     dfx deploy
     ```

5. **Run the application locally**:
   - Start the local Express.js server:
     ```bash
     npm run dev
     ```

The API will be available at `http://localhost:8000`. You can interact with the messages using the following endpoints:

- **POST /messages** - Create a new message.
- **GET /messages** - Retrieve all messages.
- **GET /messages/:id** - Retrieve a specific message by its ID.
- **PUT /messages/:id** - Update a message by its ID.
- **DELETE /messages/:id** - Delete a message by its ID.



