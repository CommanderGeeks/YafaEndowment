# Yafa Endowment Calculator

**Financial Empowerment Through Decentralized Investment**

A sophisticated web-based calculator designed to project long-term endowment performance with Palestinian-inspired design elements, built for Project Yafa's mission of financial sovereignty and community empowerment.

## 🌟 Features

### Core Functionality
- **Flexible Projection Periods**: Calculate projections for any timeframe (1-50 years)
- **Automatic Matching**: Match amount automatically equals initial investment
- **Conservative Drawdown Limits**: Maximum 10% annual withdrawal rate for sustainability
- **Real-time Calculations**: Instant updates as parameters change
- **Comprehensive Analysis**: Year-by-year breakdown with cumulative tracking

### Investment Scenarios
- **Conservative (11%)**: Stable, low-risk growth projections
- **Moderate (25%)**: Balanced growth approach
- **Aggressive (50%)**: High-growth investment strategy
- **Custom Rates**: Full flexibility to set any annual growth percentage

### Key Metrics
- **Total Withdrawn**: Complete withdrawal history over projection period
- **Remaining Balance**: Endowment value after specified years
- **ROI Calculation**: Return on investment based on initial investment only
- **Year-by-Year Breakdown**: Detailed annual progression with growth, withdrawals, and balances

## 🎨 Design Philosophy

### Visual Identity
- **Clean Green-on-White Theme**: Professional, modern aesthetic
- **Palestinian Heritage Elements**: Cultural accent bar honoring Palestinian identity
- **Responsive Design**: Optimized for all device sizes
- **Glass Morphism**: Modern frosted glass effects with backdrop blur

### Typography & Colors
- **Inter Font Family**: Clean, highly readable typography
- **Green Gradient Palette**: #22c55e to #16a34a for consistency
- **High Contrast**: Excellent readability with dark text on white background
- **Cultural Sensitivity**: Respectful integration of Palestinian design elements

## 🚀 Getting Started

### Installation
1. Clone or download the repository
2. Open `index.html` in any modern web browser
3. No additional dependencies or setup required

### Usage
1. **Set Investment Parameters**:
   - Enter initial investment amount
   - Match amount auto-populates to equal initial investment
   - Choose projection years (1-50)
   - Set annual drawdown rate (max 10%)
   - Select or customize annual growth rate

2. **Choose Investment Strategy**:
   - Click preset scenario buttons (Conservative/Moderate/Aggressive)
   - Or manually enter custom growth percentage

3. **Generate Projection**:
   - Click "Calculate Projection" button
   - Review summary cards for key metrics
   - Examine detailed year-by-year breakdown

4. **Export Results**:
   - Download CSV file for spreadsheet analysis
   - Copy data to clipboard for external use

## 📊 Calculation Methodology

### Annual Progression Formula
```
Year N:
├── Start Balance = Previous Year Final Balance
├── Growth = Start Balance × Growth Rate
├── End Balance = Start Balance + Growth
├── Withdrawal = End Balance × Drawdown Rate
└── Final Balance = End Balance - Withdrawal
```

### ROI Calculation
```
ROI = ((Final Balance + Total Withdrawn) - Initial Investment) / Initial Investment × 100
```

### Key Assumptions
- Compound annual growth applied to remaining balance
- Withdrawals calculated as percentage of post-growth balance
- No additional contributions beyond initial investment and match
- Conservative maximum drawdown rate of 10% for endowment sustainability

## 🛠️ Technical Specifications

### Technology Stack
- **Frontend**: Pure HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Grid and Flexbox
- **Typography**: Google Fonts (Inter family)
- **Compatibility**: Modern browsers (Chrome, Firefox, Safari, Edge)
- **Dependencies**: None (standalone application)

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### File Structure
```
yafa-endowment-calculator/
├── index.html          # Main application file
├── README.md          # This documentation
└── assets/            # Optional assets directory
    └── screenshots/   # Application screenshots
```

## 📱 Responsive Design

- **Desktop**: Full-width dual-column layout
- **Tablet**: Single-column stacked layout
- **Mobile**: Optimized input fields and touch-friendly buttons
- **Grid System**: CSS Grid with automatic responsive breakpoints

## 🔧 Customization

### Color Scheme Modification
Modify CSS variables in the `<style>` section:
```css
/* Primary green gradient */
background: linear-gradient(135deg, #22c55e, #16a34a);

/* Accent colors */
border-color: #22c55e;
color: #16a34a;
```

### Adding New Scenarios
Add new preset buttons in the HTML:
```html
<button class="scenario-btn" onclick="setScenario(XX)">Custom (XX%)</button>
```

### Extending Calculation Logic
Modify the `calculateProjection()` function to add new metrics or calculations.

## 📈 Use Cases

### Individual Investors
- Personal retirement planning
- Endowment fund analysis
- Investment strategy comparison
- Long-term wealth projection

### Financial Advisors
- Client presentation tool
- Investment scenario modeling
- Withdrawal strategy planning
- ROI demonstration

### Organizations
- Endowment fund management
- Scholarship fund planning
- Non-profit sustainability analysis
- Grant allocation modeling

## 🌍 Cultural Context

This calculator honors Project Yafa's mission of Palestinian financial empowerment and cultural preservation. The design elements respectfully incorporate Palestinian heritage while maintaining professional financial tool standards.

### Project Yafa Connection
- **Mission Alignment**: Supporting financial sovereignty through decentralized investment
- **Cultural Elements**: Palestinian-inspired color accents and empowerment messaging
- **Community Focus**: Tools designed for collective economic advancement

## 🔒 Privacy & Security

- **No Data Collection**: All calculations performed locally in browser
- **No External Calls**: Standalone application with no server dependencies
- **Privacy First**: No user data transmitted or stored
- **Offline Capable**: Works without internet connection after initial load

## 📋 Export Features

### CSV Export
- Filename: `yafa_endowment_projection.csv`
- Format: Comma-separated values
- Columns: Year, Start Balance, Growth, End Balance, Withdrawal, Final Balance, Cumulative Withdrawn

### Clipboard Copy
- Tab-separated format for easy paste into Excel/Google Sheets
- Formatted currency values for immediate use
- Includes all projection data

## 🤝 Contributing

This project supports Project Yafa's mission of Palestinian empowerment through financial technology. Contributions that enhance functionality while respecting the cultural context are welcome.

### Development Guidelines
- Maintain clean, readable code
- Preserve Palestinian cultural design elements
- Ensure accessibility compliance
- Test across multiple browsers and devices

## 📄 License

This calculator is provided in support of Project Yafa's educational and empowerment mission. Please respect the cultural significance and use responsibly.

## 🔗 Related Resources

- **Project Yafa**: [yafa.io](https://yafa.io)
- **Palestinian Digital Heritage**: Supporting cultural preservation through technology
- **Financial Sovereignty**: Tools for economic independence and community empowerment

---

**Built with 💚 for Palestinian financial empowerment and global community solidarity**

*"Building financial sovereignty for Palestinian communities worldwide through decentralized technology"*