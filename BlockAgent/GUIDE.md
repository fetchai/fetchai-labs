# BlockAgent User Documentation

## Introduction

BlockAgent is a powerful platform developed by Fetch AI that allows you to observe and monitor data across various blockchains, including Ethereum and Polygon. This documentation will guide you through the process of using BlockAgent efficiently.

## Prerequisites

Before getting started with BlockAgent, make sure you have the following:

1. **Fetch AI Wallet Extension**: Install the Fetch AI wallet extension on Google Chrome or Firefox browsers.
2. **FET Tokens**: Ensure that your Fetch AI wallet has a balance of at least 0.001 FET tokens to create web3 agents on the BlockAgent platform.

## Getting Started

### 1. Logging In

To access BlockAgent, log in using your Agentverse Single Sign-On (SSO) credentials.

### 2. Dashboard Overview

The Dashboard is your central hub for managing deployed web3 agents. Here's what you'll find:

- **Agent Cards**: Each card represents a deployed web3 agent and includes details such as the agent's name, address, status (running, stopped, error), blockchain name, and smart contract address.

### 3. Creating a New Agent

To create a new web3 agent, follow these steps:

#### a. Connect Your Wallet

Start by connecting your Fetch AI wallet to the BlockAgent platform.

#### b. Fill Out the Create Form

- **Blockchain**: Select the blockchain you want to monitor (e.g., Ethereum, Polygon).
- **Agent Name**: Provide a unique name for your new agent.
- **Smart Contract/Account**: Enter the smart contract address or account you wish to monitor.
- **Smart Contract Type**: Choose the type of smart contract (ERC20, ERC721, ERC1155, or ACCOUNT).
- **Webhook URL**: Specify the URL where you want to receive real-time transaction data.

#### c. Sign Transaction

Once you've filled out the form, sign the transaction from your Fetch AI wallet to initiate the creation of the new agent. This transaction will deduct the necessary FET tokens for agent creation.

#### d. Agent Deployment

Upon successful payment, the agent will be deployed on Agentverse using backend APIs. It will start monitoring the specified contracts on the selected blockchain using periodic RPC calls.

### 4. Managing Agents

You can view detailed information about each agent, including its code, logs, and running status, by clicking on the respective agent card on the Dashboard. This will redirect you to the Agentverse website, where you can access comprehensive agent details.

## Troubleshooting

If you encounter any issues during the agent creation process or need further assistance, please feel free to raise issues [here](https://github.com/fetchai/fetchai-labs/issues) .

## Conclusion

BlockAgent simplifies blockchain data monitoring by leveraging Fetch AI's advanced agent technologies. Start exploring the potential of decentralized data observation today with BlockAgent!
