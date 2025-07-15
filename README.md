# Sportfolio - Fantasy Sports Trading Platform

A fantasy sports trading platform where users can buy, hold, and trade athletes as if they were stocks, using virtual coins for safe, legal gameplay.

## Features

- **Virtual Trading System**: Buy and sell NBA athletes using virtual coins
- **Real-time Portfolio Tracking**: Monitor your holdings, gains, and losses
- **Market Data**: View trending athletes and market statistics
- **Leaderboard**: Compete with other traders
- **Trading Interface**: User-friendly interface for executing trades
- **Performance Analytics**: Track athlete stats and price movements

## Tech Stack

- **Frontend**: React, TypeScript, Tailwind CSS, Wouter (routing)
- **Backend**: Node.js, Express, TypeScript
- **Database**: In-memory storage (easily configurable for PostgreSQL)
- **UI Components**: Shadcn/ui components
- **State Management**: TanStack Query
- **Build Tool**: Vite

## Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/sportfolio.git
cd sportfolio
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

The application will be available at `http://localhost:5000`

## Project Structure

```
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # UI components
│   │   ├── pages/          # Application pages
│   │   ├── lib/            # Utilities and data logic
│   │   └── hooks/          # Custom React hooks
├── server/                 # Express backend
│   ├── index.ts           # Server entry point
│   ├── routes.ts          # API routes
│   └── storage.ts         # Data storage layer
└── shared/                # Shared types and schemas
    └── schema.ts          # Database schema definitions
```

## API Endpoints

- `GET /api/athletes` - Get all athletes
- `GET /api/athletes/trending` - Get trending athletes
- `POST /api/trade` - Execute a trade
- `GET /api/portfolio/:userId` - Get user portfolio
- `GET /api/leaderboard` - Get top traders
- `GET /api/market/stats` - Get market statistics

## Trading System

The platform uses a virtual coin system to avoid legal complications with real money trading:

- Users start with virtual coins
- Athlete prices are based on performance metrics
- Trading fees apply to all transactions
- Portfolio values update in real-time
- Price movements reflect trading volume and performance

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Disclaimer

This is a fantasy trading platform using virtual currency only. No real money is involved in trading activities.