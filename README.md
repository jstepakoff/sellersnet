# Pinnacle Seller Net Sheet Calculator

An interactive, professional real estate transaction calculator dashboard built with HTML, CSS, and JavaScript.

## Features

✨ **Interactive Calculator**
- Enter transaction details and calculate net proceeds instantly
- Support for multiple loans, commissions, and fees
- Real-time chart visualizations

📊 **Visual Analytics**
- Cost breakdown (doughnut chart)
- Money flow analysis (bar chart)
- Detailed financial summary

🎯 **Location Support**
- 52+ California cities
- 7 counties (Kern, Los Angeles, Mono, Orange, Riverside, San Bernardino, Ventura)
- LA City dual transfer tax calculation

💰 **Comprehensive Calculations**
- Sales price processing
- Loan payoff handling
- Broker commissions
- Transfer taxes
- HOA fees and proration
- Seller credits

## How to Deploy on GitHub Pages

### Option 1: Create a New Repository (Recommended)

1. **Create a new GitHub repository**
   - Go to [github.com/new](https://github.com/new)
   - Name it `seller-calculator` (or any name you prefer)
   - Click "Create repository"

2. **Clone the repository locally**
   ```bash
   git clone https://github.com/YOUR_USERNAME/seller-calculator.git
   cd seller-calculator
   ```

3. **Add the files**
   - Copy `index.html` to the repository folder
   - Create a `.gitignore` file (optional):
     ```
     .DS_Store
     node_modules/
     ```

4. **Commit and push**
   ```bash
   git add .
   git commit -m "Initial commit: Add seller calculator dashboard"
   git push origin main
   ```

5. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Select "Deploy from a branch"
   - Choose `main` branch, `/ (root)` folder
   - Click "Save"
   - Your dashboard will be live at: `https://YOUR_USERNAME.github.io/seller-calculator/`

### Option 2: Upload to Existing Repository

If you have an existing GitHub repository:

1. **Copy `index.html` to the root folder** of your repository (or create a `docs/` folder and place it there)

2. **Push to GitHub**
   ```bash
   git add index.html
   git commit -m "Add seller calculator"
   git push origin main
   ```

3. **Enable GitHub Pages** (as described in Option 1, step 5)

## Usage

1. **Fill in transaction details**
   - Enter seller name and property address
   - Select city and county
   - Input sales price and property taxes

2. **Enter loan information**
   - Input any existing loans to be paid off
   - HOA fees and proration days

3. **Set commission rates**
   - Seller's broker commission percentage
   - Buyer's broker commission percentage
   - Pinnacle base commission

4. **Click "Calculate Net Proceeds"**
   - View detailed breakdown of all deductions
   - See visual charts of costs and money flow

## Features Included

- ✅ Responsive design (works on desktop and mobile)
- ✅ No backend required (pure client-side calculations)
- ✅ Interactive charts with Chart.js
- ✅ Professional styling and UI
- ✅ Currency formatting
- ✅ Real-time calculations
- ✅ CA transfer tax calculations
- ✅ LA City dual tax support

## Customization

To modify the calculator:

1. **Edit cities/counties**: Update the `locationData` object in the JavaScript section
2. **Change tax rates**: Modify the transfer tax calculation in the `calculate()` function
3. **Update styling**: Edit CSS variables in the `:root` section
4. **Add new fields**: Add form inputs and update the `calculate()` function

## Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript
- **Charts**: Chart.js 3.9.1
- **No dependencies**: Runs in any modern browser
- **File size**: ~50KB (highly optimized)

## License

This calculator is provided as-is for real estate professionals and sellers.

## Support

For issues or questions:
1. Check the console (F12 → Console tab) for errors
2. Verify all input values are correct
3. Try clearing the form and recalculating

---

**Ready to deploy?** Follow the GitHub Pages setup steps above to get your dashboard live in minutes!
