# 📈 Market Making Academy

An interactive web-based platform for learning market-making concepts through hands-on practice. Master the art of bid-ask spreads, position management, and P&L calculations with real-time feedback.

## 🎯 Features

### Interactive Learning Platform
- **33 Diverse Scenarios**: From estimating the Eiffel Tower's height to global populations
- **Real-Time Feedback**: Learn from every trade with immediate explanations
- **Comprehensive Theory Guide**: Built-in tutorial covering all essential concepts
- **Progressive Difficulty**: Start with wide spreads, tighten as you learn

### Key Concepts Covered
1. **Position Tracking**: Master long/short position management
2. **Cash Calculation**: Track money flow from trades
3. **Average Price**: Calculate effective trading prices
4. **Realized P&L**: FIFO-based closed position accounting
5. **Unrealized P&L**: Value open positions at market prices
6. **Total P&L**: Quick formula and detailed breakdowns
7. **Break-Even Analysis**: Calculate exit prices for zero P&L

### Learning Tools
- **After-Round Questions**: Test your understanding after each trade
- **Detailed Explanations**: Step-by-step breakdowns when wrong
- **Strategy Tips**: Learn from adverse selection signals
- **Complete Example**: Walk through the "Kangaroos in Australia" scenario

## 🚀 Quick Start

### Option 1: Direct Use
1. Clone the repository
2. Open `index.html` in any modern web browser
3. Click "📚 Learn the Theory First" to read the guide
4. Select a scenario and start trading!

### Option 2: GitHub Pages
Visit: `https://jonathan2667.github.io/market-making-game/`

## 📚 How It Works

### Game Flow
1. **Set Confidence Interval**: Establish your 95% confidence range for the true value
2. **Make Markets**: Quote bid-ask spreads (e.g., "100 - 110")
3. **Computer Trades**: The computer rationally trades when profitable
4. **Answer Questions**: Calculate position, cash, realized/unrealized P&L
5. **Final Summary**: Review your performance and learn from mistakes

### Example: Kangaroos in Australia 🦘

**Scenario**: Estimate kangaroo population in Australia (millions)

```
Round 1: Market 20-25 → Computer buys → You SOLD at 25
Round 2: Market 30-35 → Computer buys → You SOLD at 35
Round 3: Market 40-45 → Computer buys → You SOLD at 45
Round 4: Market 60-65 → Computer sells → You BOUGHT at 60

True Value: 42 million kangaroos
```

**Your Results**:
- Position: -2 (short 2 units)
- Cash: 45 million
- Average Price: 22.5 million
- Realized P&L: -35 million
- Unrealized P&L: -4 million
- **Total P&L: -39 million**

**Lesson**: You kept selling too low! The computer buying from you signals your prices are below true value.

## 🎓 Key Formulas

| Concept | Formula |
|---------|---------|
| **Position** | Computer buys → -1 (short) \| Computer sells → +1 (long) |
| **Cash** | Σ(Sells) - Σ(Buys) |
| **Average Price** | Cash ÷ \|Position\| |
| **Realized P&L** | Sum of closed pairs (FIFO) |
| **Unrealized P&L** | Longs: Σ(Value - Buy Price) \| Shorts: Σ(Sell Price - Value) |
| **Total P&L** | **Cash + (Position × True Value)** ⚡ |

## 💡 Strategy Tips

1. **Learn from trades**: Computer buying → your prices too low | Computer selling → your prices too high
2. **Manage position**: Getting too long/short? Adjust your mid-price accordingly
3. **Spread sizing**: Start wide for protection, tighten as you gain confidence
4. **Avoid adverse selection**: If consistently hit on one side, move your market!

## 🔧 Technical Details

- **Single-file application**: Pure HTML/CSS/JavaScript
- **No dependencies**: Works offline, no framework needed
- **📱 Fully Mobile-Friendly**: Optimized responsive design for phones and tablets
  - Touch-friendly buttons and inputs
  - Scrollable tables for theory examples
  - Readable text sizes on small screens
  - Vertical layouts for narrow displays
- **Local storage**: Game state persists in browser

## 🎮 Scenarios

### Sample Scenarios:
- 🗼 Eiffel Tower Height
- ✈️ Boeing 747 Passenger Capacity
- 🌍 Country Populations
- 🏃 Marathon World Records
- 🦘 **Kangaroos in Australia** (Tutorial Example)
- ...and 28 more!

## 📖 Educational Use

Perfect for:
- **Finance Students**: Learn market-making fundamentals
- **Traders**: Practice position management and P&L tracking
- **Interviewers**: Test candidate understanding of trading concepts
- **Self-learners**: Hands-on learning with immediate feedback

## 🤝 Contributing

Suggestions for new scenarios or improvements? Open an issue or submit a pull request!

## 📄 License

This project is open source and available for educational purposes.

## 🙏 Acknowledgments

Created as an interactive learning tool for mastering market-making concepts through practical application.

---

**Start Learning**: [Play Now](index.html) | [Read Theory](index.html#theory)

