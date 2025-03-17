# MarketPulse - Financial Dashboard with Blockchain Integration

MarketPulse is a modern financial dashboard application that provides real-time market insights and analytics with blockchain authentication using MetaMask.

![MarketPulse Dashboard](https://via.placeholder.com/800x400?text=MarketPulse+Dashboard)

## Features

- **Real-time Market Data**: Track stocks, cryptocurrencies, and other financial instruments
- **Interactive Charts**: Visualize market trends with customizable charts
- **Portfolio Tracking**: Monitor your investments in one place
- **Technical Indicators**: Access advanced technical analysis tools
- **Price Alerts**: Set up notifications for price movements
- **Blockchain Authentication**: Secure sign-in and sign-up with MetaMask wallet
- **Dark/Light Mode**: Toggle between dark and light themes

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- MetaMask browser extension installed

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/marketpulse.git
   cd marketpulse
   ```

2. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:5173`

## Using MetaMask Integration

### Connecting Your Wallet

1. Click the "Sign In" or "Sign Up" button in the top-right corner of the dashboard
2. In the authentication modal, click "Connect MetaMask"
3. Approve the connection request in your MetaMask extension
4. For new users, you'll be prompted to create an account by providing a username
5. For returning users, you'll be asked to sign a message to verify your identity

### Authentication Flow

- **Sign Up**: Connect wallet → Enter username → Sign verification message → Account created
- **Sign In**: Connect wallet → Sign verification message → Authentication complete

### Security Features

- Message signing for secure authentication
- No private keys are ever exposed or stored
- Blockchain-based identity verification

## Project Structure

```
marketpulse/
├── public/             # Static assets
├── src/
│   ├── assets/         # Images, fonts, etc.
│   ├── components/     # React components
│   │   ├── auth/       # Authentication components
│   │   ├── charts/     # Chart components
│   │   ├── dashboard/  # Dashboard layout components
│   │   └── widgets/    # Dashboard widgets
│   ├── context/        # React context providers
│   ├── hooks/          # Custom React hooks
│   ├── services/       # API and service functions
│   ├── styles/         # CSS and style files
│   ├── types/          # TypeScript type definitions
│   ├── utils/          # Utility functions
│   ├── App.tsx         # Main App component
│   └── main.tsx        # Application entry point
├── .gitignore          # Git ignore file
├── package.json        # Project dependencies
├── tsconfig.json       # TypeScript configuration
└── vite.config.ts      # Vite configuration
```

## Deployment

To build the application for production:

```bash
npm run build
# or
yarn build
```

The build artifacts will be stored in the `dist/` directory.

## Technologies Used

- **React**: UI library
- **TypeScript**: Type-safe JavaScript
- **Vite**: Build tool and development server
- **React Bootstrap**: UI component library
- **Recharts**: Charting library
- **Ethers.js**: Ethereum library for blockchain interaction
- **MetaMask**: Web3 wallet for authentication

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [React](https://reactjs.org/)
- [MetaMask](https://metamask.io/)
- [Ethers.js](https://docs.ethers.io/)
- [React Bootstrap](https://react-bootstrap.github.io/)
- [Recharts](https://recharts.org/)

---

## Pushing to GitHub

To push this project to your GitHub repository:

1. Create a new repository on GitHub (don't initialize it with README, license, or gitignore)

2. Initialize git in your local project (if not already done):
   ```bash
   git init
   ```

3. Add all files to git:
   ```bash
   git add .
   ```

4. Commit the files:
   ```bash
   git commit -m "Initial commit: MarketPulse with MetaMask integration"
   ```

5. Add your GitHub repository as remote:
   ```bash
   git remote add origin https://github.com/yourusername/marketpulse.git
   ```

6. Push to GitHub:
   ```bash
   git push -u origin main
   # or if you're using master branch
   git push -u origin master
   ```

Note: Replace `yourusername` with your actual GitHub username and adjust the repository name if needed.
