# Gold/Silver Dashboard

Real-time precious metals price dashboard with news feed and buy/hold/sell advice.

## Features

- 🥇 Live gold (XAU) prices in EUR
- 🥈 Live silver (XAG) prices in EUR
- 📈 Price history charts
- 📰 Latest news headlines
- 💡 Buy/Hold/Sell advice with confidence score
- 🔄 Auto-refresh every 5 minutes

## Quick Start

```bash
npm install
npm start
```

## Docker Deployment

```bash
docker-compose up -d
```

## Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| PORT | Server port | No (default: 3002) |
| GOLD_API_KEY | goldapi.io API key | No (uses free fallback) |
| NEWS_API_KEY | newsapi.org API key | No (uses placeholder news) |

## API Endpoints

- `GET /api/dashboard` - Get all data (prices, news, advice)
- `POST /api/refresh` - Force refresh data
- `GET /health` - Health check

## Disclaimer

⚠️ This dashboard is for informational purposes only and does not constitute financial advice. 
Always consult with a qualified financial advisor before making investment decisions.

## License

MIT
