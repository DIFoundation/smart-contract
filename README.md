# Ambience Chat Smart Contract

A decentralized, onchain chat smart contract built for Base blockchain that enables secure, transparent, and censorship-resistant communication. All messages are stored directly onchain, ensuring immutability and verifiability.

## Overview

This smart contract powers the Ambience Chat dApp, a fully decentralized messaging platform where all chat data lives onchain. The contract manages chat rooms, user profiles, messages, and moderation mechanisms without relying on centralized infrastructure.

## Features

- **Onchain Message Storage**: All messages permanently stored on Base blockchain
- **Chat Room Management**: Create, join, and manage multiple chat rooms
- **User Profile System**: Onchain identity with username and profile metadata
- **Room-based Organization**: Segregate conversations into different rooms/channels
- **Access Control**: Public and private room support
- **Event Emission**: Real-time updates via blockchain events
- **Gas Optimized**: Efficient storage patterns to minimize transaction costs
- **Moderation Tools**: Decentralized room moderation mechanisms
- **Message History**: Complete, immutable chat history accessible to all

## Tech Stack

- **Solidity**: ^0.8.13 or higher
- **Foundry**: Development framework for building, testing, and deploying
- **forge-std**: Standard library for Foundry testing
- **Base Blockchain**: Layer 2 network (Sepolia testnet for development, Mainnet for production)