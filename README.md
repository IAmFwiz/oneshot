# OneShot - Predictive Insights Platform

OneShot is a comprehensive predictive insights platform that aggregates data from multiple sources to provide intelligent market predictions and portfolio insights.

## 🎯 Project Overview

OneShot leverages advanced AI and machine learning to analyze market data, sports statistics, and prediction markets to deliver actionable insights for investors and analysts.

## 🔧 Required APIs & Services

- [ ] **Google Gemini API Key** - For the Predictive Insights Engine
- [ ] **Kalshi API Key** - For market and portfolio data
- [ ] **Polymarket API Credentials** - L1 Private Key and generated L2 API Key/Secret/Passphrase
- [ ] **X.com API Bearer Token** (Optional) - For the expert content feed
- [ ] **SportsData.io API Key** - For NFL and CFB sports data
- [ ] **Self-Hosted Server** - A machine with Docker and Docker Compose installed
- [ ] **Tailscale Account** - For secure remote access

## 🚀 Features

- **Predictive Insights Engine** - AI-powered market predictions
- **Multi-Source Data Integration** - Aggregates data from various APIs
- **Real-time Market Analysis** - Live market data processing
- **Sports Data Integration** - NFL and CFB statistics
- **Expert Content Feed** - Curated insights from industry experts
- **Secure Remote Access** - Tailscale integration for secure connections

## 🛠️ Tech Stack

- **Backend**: Node.js/TypeScript
- **AI/ML**: Google Gemini API
- **Data Sources**: Kalshi, Polymarket, SportsData.io, X.com
- **Infrastructure**: Docker, Docker Compose
- **Security**: Tailscale for secure access

## 📁 Project Structure

```
oneshot/
├── src/
│   ├── api/           # API integrations
│   ├── services/      # Business logic
│   ├── models/        # Data models
│   └── utils/         # Utility functions
├── config/            # Configuration files
├── docs/              # Documentation
├── tests/             # Test files
└── docker/            # Docker configuration
```

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd oneshot
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your API keys
   ```

4. **Run the application**
   ```bash
   npm start
   ```

## 🔐 Environment Variables

Create a `.env` file with the following variables:

```env
# Google Gemini API
GEMINI_API_KEY=your_gemini_api_key

# Kalshi API
KALSHI_API_KEY=your_kalshi_api_key

# Polymarket API
POLYMARKET_L1_PRIVATE_KEY=your_l1_private_key
POLYMARKET_L2_API_KEY=your_l2_api_key
POLYMARKET_L2_SECRET=your_l2_secret
POLYMARKET_L2_PASSPHRASE=your_l2_passphrase

# X.com API (Optional)
X_API_BEARER_TOKEN=your_x_bearer_token

# SportsData.io API
SPORTSDATA_API_KEY=your_sportsdata_api_key

# Server Configuration
PORT=3000
NODE_ENV=development
```

## 📊 Data Sources

- **Kalshi** - Prediction market data
- **Polymarket** - Decentralized prediction markets
- **SportsData.io** - NFL and CFB statistics
- **X.com** - Expert content and social sentiment
- **Google Gemini** - AI-powered analysis

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support, email support@oneshot.com or join our Slack channel.

---

**OneShot** - Making predictions with precision. 🎯
