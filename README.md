# 💰 Personal Financial Tracker v2.2

A comprehensive, self-contained HTML financial management application with advanced analytics, CSV import/export, and intuitive dashboard visualizations.

![Financial Tracker Demo](https://img.shields.io/badge/version-2.2-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![HTML5](https://img.shields.io/badge/HTML5-orange) ![JavaScript](https://img.shields.io/badge/JavaScript-yellow) ![Chart.js](https://img.shields.io/badge/Chart.js-red)

## 🚀 Features

### 📊 Core Financial Management
- **Monthly Budget Planning** - Set budgets across 12+ spending categories
- **Transaction Tracking** - Log income and expenses with detailed categorization
- **Bank Account Balance** - Real-time balance tracking with transaction integration
- **ETF Portfolio Tracking** - Monitor investment growth with automatic calculations

### 📈 Advanced Analytics
- **50/30/20 Rule Analysis** - Automated budget breakdown and recommendations
- **Historical Trends** - Multi-month spending pattern analysis
- **Predictive Forecasting** - AI-powered spending predictions using linear regression
- **Financial Health Score** - Comprehensive financial wellness assessment
- **Smart Recommendations** - Personalized optimization suggestions

### 🎯 Dashboard & Visualization
- **Interactive Charts** - Powered by Chart.js with responsive design
- **Budget vs Actual Analysis** - Real-time comparison across all categories
- **Month-to-Month Comparison** - Historical performance tracking
- **Export Capabilities** - CSV export for external analysis

### 💾 Data Management
- **CSV Import/Export** - Bulk data import with template support
- **Local Storage** - Automatic data persistence in browser
- **Transaction Filtering** - Advanced filtering by month and category
- **Auto-save** - Real-time data protection

## 🎮 Live Demo

Open `financial-tracker.html` in any modern web browser - no server required!

## 📥 Quick Start

### Option 1: Direct Download
1. Download `financial-tracker.html`
2. Open in your web browser
3. Start tracking your finances immediately!

### Option 2: Clone Repository
```bash
git clone https://github.com/Abhisheksiddaraju/Financial-Tracker.git
cd Financial-Tracker
# Open financial-tracker.html in your browser
```

## 🚀 Getting Started

### Option A: Manual Setup
1. Open the app in your browser
2. Navigate to "Monthly Budget" tab
3. Enter your income and budget amounts
4. Start adding transactions in "Transactions" tab

### Option B: CSV Import (Recommended for Existing Data)
1. Open the app in your browser
2. Click "📝 Download CSV Template" button
3. Fill in your financial data using the template
4. Import via "📥 Import from CSV" button

## 📋 How to Use

### 1. **Set Up Your Budget**
   - Navigate to "Monthly Budget" tab
   - Enter your income and monthly budget for each category
   - The app automatically calculates totals and recommendations

### 2. **Track Transactions**
   - Use "Transactions" tab to log daily expenses and income
   - Categories align with your budget for seamless analysis
   - Edit transactions inline if needed

### 3. **Monitor ETF Portfolio**
   - Record portfolio values monthly in "ETF Portfolio" tab
   - Automatic growth rate calculations
   - Integration with budget savings analysis

### 4. **Analyze Performance**
   - "Dashboard" provides comprehensive financial overview
   - Month navigation and comparison tools
   - Real-time budget vs actual analysis

### 5. **Advanced Insights**
   - "Analytics" tab unlocks after 3 months of data
   - Historical trends and predictive forecasting
   - Financial health scoring and recommendations

## 🏗️ Technical Architecture

### Single-File Application
- **Pure HTML5/CSS3/JavaScript** - No dependencies or server required
- **Chart.js CDN** - Professional charting capabilities
- **Local Storage API** - Data persistence without databases
- **Responsive Design** - Works on desktop, tablet, and mobile

### Data Structure
```javascript
// Example data format
{
  budget: {
    salary: 2700,
    budgetRent: 535,
    budgetUtilities: 48,
    // ... other budget categories
  },
  transactions: [
    {
      date: "2025-08-01",
      desc: "Grocery shopping",
      category: "Groceries",
      amount: 25.50,
      paymentMethod: "Card"
    }
  ],
  etfTransactions: [
    {
      date: "2025-08-01",
      value: 1000.00,
      notes: "Monthly investment"
    }
  ]
}
```

## 🎨 Customization

### Adding New Categories
1. Update transaction dropdown options in HTML
2. Add budget input field
3. Include in calculation functions
4. Update CSV import/export mappings

### Modifying Analytics
- Edit `updateAdvancedAnalytics()` function
- Customize financial health scoring in `updateFinancialHealthScore()`
- Add new chart types using Chart.js documentation

### Styling Changes
- All CSS is embedded in the HTML file
- Modify CSS variables for color scheme changes
- Responsive design uses CSS Grid and Flexbox

## 📊 Analytics Features

### Historical Trends
- **Multi-period Analysis** (3, 6, 12 months, all time)
- **Category-specific Trends** with volatility analysis
- **Pattern Recognition** for seasonal spending

### Predictive Analytics
- **Linear Regression Forecasting** for future spending
- **Scenario Planning** with what-if analysis
- **Risk Assessment** based on spending patterns

### Financial Health Score
Calculated from:
- Budget adherence (25 points)
- Savings rate (25 points)
- Income stability (25 points)
- Emergency fund coverage (25 points)

## 🔧 Browser Compatibility

✅ **Supported Browsers:**
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

⚠️ **Required Features:**
- Local Storage API
- ES6+ JavaScript
- Canvas API (for charts)
- File API (for CSV import)

## 📱 Mobile Experience

- **Responsive Design** - Optimized for all screen sizes
- **Touch-Friendly** - Large buttons and intuitive navigation
- **Offline Capable** - Works without internet connection
- **Data Persistence** - Survives browser restarts

## 🛡️ Privacy & Security

### Data Privacy
- **100% Local Storage** - No data sent to external servers
- **No Tracking** - No analytics or third-party scripts
- **Offline Operation** - Complete privacy protection

### Data Security
- **Browser-Based Encryption** - Local storage security
- **No Account Required** - Anonymous usage
- **Export Control** - You own your data completely

## 🗓️ Version History

### v2.2 (Current)
- ✨ Added CSV import/export functionality
- 🔄 Enhanced transaction filtering and month navigation
- 📊 Advanced analytics with historical trends
- 🎯 Financial health scoring system
- 💡 Smart recommendations engine

### v2.1
- 📈 Advanced analytics tab with forecasting
- 🔍 Month comparison and navigation
- 📊 Enhanced dashboard with multiple chart types
- 🎯 50/30/20 rule analysis

### v2.0
- 🏦 Bank account balance tracking
- 💼 ETF portfolio management
- 📊 Budget vs actual analysis
- 🎨 Enhanced UI with better visualization

### v1.0
- 📋 Basic transaction tracking
- 💰 Monthly budget management
- 📊 Simple dashboard with charts

## 🤝 Contributing

This is an open-source project! Contributions welcome:

1. **Fork the repository**
2. **Create feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit changes** (`git commit -m 'Add amazing feature'`)
4. **Push to branch** (`git push origin feature/amazing-feature`)
5. **Open Pull Request**

### Development Guidelines
- Maintain single-file architecture
- Test across multiple browsers
- Follow existing code style
- Update documentation for new features

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Abhishek Siddaraju** - *Creator & Developer*
- **Claude (Anthropic AI)** - *AI Assistant & Co-developer*

## 🙏 Acknowledgments

- **Chart.js** - For excellent charting capabilities
- **Modern CSS** - For responsive design inspiration
- **Financial Community** - For feature suggestions and testing

## 📞 Support

Having issues? Here's how to get help:

1. **Check Browser Console** - Look for JavaScript errors
2. **Clear Local Storage** - Reset application state
3. **Try Different Browser** - Compatibility testing
4. **Create GitHub Issue** - Report bugs or request features

## 🔮 Roadmap

### Planned Features (v3.0)
- 🏠 **Net Worth Tracking** - Assets and liabilities management
- 🎯 **Goal Setting** - Savings and investment targets
- 📊 **Investment Analysis** - Portfolio performance tracking
- 🔄 **Data Sync** - Cloud backup options
- 📱 **PWA Support** - Installable web app

---

**Made with ❤️ for better financial health**

*Star ⭐ this repo if it helps you manage your finances better!*
