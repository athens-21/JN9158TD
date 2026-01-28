# Trading Journal System

[![Bloomberg Terminal Theme](https://img.shields.io/badge/Theme-Bloomberg-orange)](https://github.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

Professional trading journal web application with **automatic MT5 synchronization** and **Bloomberg Terminal theme**.

## ✨ Features

- 🎯 **Direct MT5 Login** - Enter account number and start trading
- 📊 **Real-time Analytics** - Live trading statistics and performance metrics
- 🔄 **Auto Sync** - MT5 Expert Advisor syncs trades automatically
- 📈 **Bloomberg Theme** - Professional dark terminal interface
- 💰 **Complete Trade Journal** - Track all trades with detailed metrics
- 📱 **Responsive Design** - Works on desktop, tablet, and mobile

## 🚀 Quick Start

```bash
# Clone and navigate
cd "New TJ"

# Start everything
START_ALL.bat

# Access the app
# Frontend: http://localhost:5174
# Backend:  http://localhost:3002
```

## 📋 Requirements

- Node.js 18+
- PostgreSQL 12+
- MetaTrader 5

## 📦 Installation

See [INSTALL.md](INSTALL.md) for detailed setup instructions.

## 🎨 Screenshots

**Bloomberg Terminal Theme**
- Dark navy background with professional financial layout
- Orange accent colors for important elements
- Monospace fonts for trading data
- Clean, organized dashboard

## 📊 Tech Stack

### Backend
- Node.js + Express
- PostgreSQL with UUIDs
- JWT Authentication
- RESTful API

### Frontend
- React 18 + Vite
- TailwindCSS
- React Router v6
- Axios
- Chart.js

### MT5 Integration
- MQL5 Expert Advisor
- Webhook-based sync
- Real-time trade updates

## 🔧 Configuration

### Ports
- Backend: **3002**
- Frontend: **5174**
- Database: **5432** (PostgreSQL)

### Environment Files
- `backend/.env` - Database and server config
- `frontend/vite.config.js` - Frontend port config

## 📖 Documentation

- **[Installation Guide](INSTALL.md)** - Detailed setup instructions
- **[Quick Start](QUICK_START.md)** - Fast setup for experienced users

## 🎯 Usage

1. **Login**
   - Enter your MT5 account number
   - System creates account automatically if it doesn't exist

2. **Dashboard**
   - View KPI cards with trading statistics
   - See recent trades
   - Monitor account performance

3. **Journal**
   - Browse all trades
   - Filter by status and pair
   - Add manual trades
   - Edit/delete trades

4. **Analytics**
   - View advanced performance metrics
   - Analyze trading patterns
   - AI insights (coming soon)

5. **Settings**
   - Configure account details
   - Manage preferences
   - View API settings

## 🔄 MT5 Synchronization

The Expert Advisor automatically syncs:
- ✅ Trade opens (ORDER_OPEN events)
- ✅ Trade closes (ORDER_CLOSE events)
- ✅ Entry/exit prices
- ✅ Profit/loss calculations
- ✅ Commission and swap

## 🎨 Bloomberg Terminal Theme

Inspired by professional trading terminals:
- **Dark Mode** - Easy on the eyes for long trading sessions
- **Professional Typography** - Inter and Roboto Mono fonts
- **Financial Color Scheme** - Dark navy, orange accents, teal success
- **Grid Layouts** - Organized, scannable information
- **Terminal Style** - Monospace data display

## 🔐 Security Note

⚠️ **This is a proof-of-concept system**

- Direct MT5 account number login (no password)
- Suitable for personal use and development
- **Not production-ready** - Implement proper auth for production

## 📝 License

MIT License - Free to use and modify

## 🤝 Contributing

Contributions welcome! Feel free to:
- Report bugs
- Suggest features
- Submit pull requests

## 🆘 Support

Having issues? Check:
1. [Troubleshooting](INSTALL.md#troublesho oting) in installation guide
2. [Common Issues](QUICK_START.md#common-issues) in quick start
3. Console logs for detailed errors

## 🎯 Roadmap

- [x] MT5 auto-sync
- [x] Bloomberg Terminal theme
- [x] Real-time statistics
- [x] Trade management
- [ ] Advanced charting
- [ ] AI trading insights
- [ ] Multi-account support
- [ ] Mobile app
- [ ] Trade alerts
- [ ] Strategy backtesting

---

**Built with ❤️ for traders**
