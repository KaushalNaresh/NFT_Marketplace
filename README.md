# NFT Marketplace

Welcome to the NFT Marketplace project repository. This platform is part of ECS 265 course project that provides a seamless and secure environment for trading NFTs, leveraging the Ethereum blockchain and cloud services.

![NFT Marketplace](https://github.com/KaushalNaresh/NFT_Marketplace/blob/main/src/images/HomeScreen.png)

## Overview

The NFT Marketplace is a full-stack application that allows users to mint, buy, and sell NFTs. The front-end is built with Next.js, providing a responsive and interactive user experience, while the back-end is a set of Solidity smart contracts on the Ethereum blockchain, ensuring secure and transparent transactions.

## Features

- **Mint NFTs**: Users can create their own NFTs by uploading digital assets.
- **Browse NFTs**: The marketplace displays a variety of NFTs available for purchase.
- **Wallet Integration**: Users can connect their Metamask wallet for transactions.

## Tech Stack

- **Front-End**: Next.js
- **Smart Contracts**: Solidity
- **Blockchain**: Ethereum
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Cloud Provider**: AWS (EC2, AWS Secrets Manager)

## Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/KaushalNaresh/NFT_Marketplace.git
cd NFT_Marketplace
# Install dependencies for the project
npm install
```

Run the development server:

```bash
npm run dev
```

or

```bash
yarn dev
```

Open http://localhost:3000 with your browser to see the result.

## Deployment

The project is containerized using Docker and orchestrated with Kubernetes, allowing it to be deployed on any cloud provider that supports these tools. AWS is used for the cloud infrastructure, taking advantage of services like EC2 and AWS Secrets Manager for secure and scalable deployment.

## Contact

For further details you can refer this [Medium Blog](https://medium.com/@vikramansenn/resource-efficient-nft-marketplace-on-ethereum-amazon-web-services-89312798e857)
For any queries or further assistance, please contact [Naresh Kumar Kaushal](09naresh3@gmail.com).

