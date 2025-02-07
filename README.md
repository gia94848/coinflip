
# Coin Flip on Aptos

## Overview

Coin Flip is a decentralized gambling game built on the Aptos blockchain. The platform offers fair and transparent betting experiences with features like Coin Flip and Roulette.

## Features

-   **Coin Flip**: A simple 50/50 chance game where players bet on heads or tails.
    
-   **Roulette**: A more complex game with multiple betting options and higher payout possibilities.
    
-   **Decentralized & Transparent**: All transactions and game logic are executed on-chain, ensuring fairness.
    
-   **Fast & Secure**: Leveraging the Aptos blockchain for low-latency and high-speed transactions.
    
-   **Smart Contract-Based**: Utilizes Move smart contracts to handle game logic and payouts securely.
    

## Getting Started

### Prerequisites

-   An Aptos wallet (e.g., Martian, Petra)
    
-   Aptos tokens for placing bets
    

### Installation

1.  Clone the repository:
    
    ```
    git clone https://github.com/gia94848/coinflip.git
    cd coinflip
    ```
    
2.  Install dependencies:
    
    ```
    npm install
    ```
    
3.  Deploy the smart contracts (if applicable):
    
    ```
    aptos move publish --profile default
    ```
    
4.  Run the frontend:
    
    ```
    npm start
    ```
    

## How to Play

1.  Connect your Aptos wallet.
    
2.  Choose a game mode (Coin Flip or Roulette).
    
3.  Place your bet and confirm the transaction.
    
4.  The smart contract executes the game logic and determines the result.
    
5.  Winnings are automatically transferred to your wallet.
    

## Smart Contract

The smart contracts are written in Move and deployed on the Aptos blockchain. The key functions include:

-   `flip_coin()`: Handles Coin Flip game logic.
    
-   `play_roulette()`: Manages Roulette game outcomes.
    
-   `place_bet()`: Ensures secure bet placements.
    
-   `payout_winner()`: Distributes winnings fairly.
    

## Roadmap

-   Add support for additional betting games.
    
-   Implement a rewards system for frequent players.
    
-   Enhance UI/UX for a smoother gaming experience.
    
-   Improve smart contract efficiency and security.
    

## License

This project is licensed under the MIT License.
