# CALC Portfolio - THORChain DCA Strategy Tracker

A professional portfolio tracking application for monitoring DCA (Dollar-Cost Averaging) strategies on THORChain, Rujira.network, and CALC Finance.

## Overview

CALC Portfolio enables users to track the performance of their crypto portfolios by monitoring recurring trades executed on the THORChain blockchain through Rujira.network. The application provides real-time analytics, PNL tracking, and comprehensive insights into DCA strategy performance.

## Key Features

### Core Functionality

- **Multi-Address Tracking**: Enter one or multiple THORChain/Rujira addresses to monitor all DCA strategies in one place
- **Stablecoin Balance Tracking**: Monitor the total stablecoin balance added to addresses over time
- **Average Entry Price Calculation**: Automatically calculate average entry prices for each asset you've DCA'd into
- **Portfolio Balance Comparison**: Compare current portfolio balance against total stablecoin inputs
- **Individual Asset PnL**: View profit and loss for each individual asset with detailed breakdowns
- **Aggregate Portfolio PnL**: Track overall portfolio performance with aggregate profit and loss calculations

### Key Capabilities

1. **Address Management**
   - Add multiple THORChain addresses
   - Automatic activity detection
   - Address-specific analytics

2. **Strategy Tracking**
   - Monitor stablecoin deposits
   - Track automatic conversions to target assets
   - View accumulated positions over time

3. **Analytics Dashboard**
   - Real-time portfolio value
   - Historical performance charts
   - Trade execution history
   - Slippage analysis
   - Asset allocation breakdown

4. **PNL Calculations**
   - Input vs. output value comparison
   - Time-weighted returns
   - Asset-specific performance
   - Overall portfolio performance

## Technology Stack

### Frontend
- HTML5
- CSS3 (Custom styling with CSS variables)
- Vanilla JavaScript (to be implemented)

### Built On
- **THORChain**: Decentralized cross-chain liquidity protocol
- **Rujira.network**: DCA automation platform for THORChain
- **CALC Finance**: Advanced portfolio analytics and tracking

## Project Structure

```
Calc Portfolio/
├── index.html          # Main landing page (explains the project)
├── portfolio.html      # Portfolio tracker app (work in progress)
├── styles.css          # Styling and design system
├── README.md          # Project documentation
└── (future additions)
    ├── app.js         # Application logic
    ├── api/           # API integration layer
    └── components/    # Reusable UI components
```

## Application Structure

- **Landing Page** (`index.html`): Explains what CALC Portfolio is, the technologies it's built on (THORChain, Rujira.network, CALC Finance), and the key features
- **Portfolio Tracker** (`/portfolio`): The actual tracking application (currently showing "work in progress")

## Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Valid THORChain address(es) to track

### Installation

1. Clone or download the project
2. Open `index.html` in your web browser
3. No build process required for the landing page

### Usage

1. Open `index.html` in your browser to view the landing page
2. Click "Launch Portfolio Tracker" to navigate to the portfolio tracker
3. The portfolio tracker is currently under development (work in progress page shown)

## Roadmap

### Phase 1: Foundation (Current)
- [x] Landing page design
- [ ] Core UI framework
- [ ] THORChain address validation

### Phase 2: Core Features
- [ ] Rujira.network API integration
- [ ] Real-time trade tracking
- [ ] PNL calculation engine
- [ ] Average execution price tracking

### Phase 3: Analytics
- [ ] Performance charts
- [ ] Historical data visualization
- [ ] Strategy comparison tools
- [ ] Export functionality

### Phase 4: Advanced Features
- [ ] Multi-strategy support
- [ ] Portfolio optimization suggestions
- [ ] Alert system for significant events
- [ ] Mobile responsive design

## Use Cases

### DCA Investors
Track automated dollar-cost averaging strategies without manual spreadsheet management. Monitor how stablecoins convert to target assets over time.

### Portfolio Managers
Oversee multiple addresses and strategies from a unified dashboard with comprehensive analytics and performance tracking.

### Strategy Optimizers
Analyze historical performance data to identify patterns, optimize entry points, and refine asset allocation strategies.

## Technical Details

### DCA Strategy Flow

1. **Input**: User deposits stablecoins to tracked address
2. **Strategy Execution**: Automated swaps via Rujira.network convert stables to target assets
3. **Tracking**: System monitors each trade for:
   - Execution price
   - Amount converted
   - Timestamp
   - Slippage
4. **Analytics**: Calculate running averages, PNL, and performance metrics

### Supported Assets

- **Input**: Stablecoins (USDC, USDT, DAI, etc.)
- **Output**: BTC, ETH, and other THORChain-supported assets

## Contributing

This is a personal project, but suggestions and feedback are welcome.

## License

TBD

## Contact & Resources

- [THORChain Documentation](https://docs.thorchain.org)
- [Rujira Network](https://rujira.network)

## Acknowledgments

Built for the THORChain community to provide transparent and accessible portfolio tracking for DCA strategies.

---

**Note**: This project is currently in development. Features and functionality will be added incrementally.
