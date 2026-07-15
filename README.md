# 🏦 Default Risk Predictor

AI-powered company default risk prediction — runs entirely in your browser.

## 🌐 Live Demo

**[Click here to use the app](https://YOUR_USERNAME.github.io/default-risk-predictor)**

*(Replace YOUR_USERNAME with your actual GitHub username after deployment)*

## 🔒 Privacy First

- ✅ **No backend server** — all processing happens in your browser
- ✅ **No data sent anywhere** — your financial data never leaves your computer
- ✅ **Works offline** — once loaded, no internet needed
- ✅ **100% free** — no subscriptions, no API keys

## 📊 What It Does

Upload a CSV file with 3 years of financial data (2023, 2024, 2025) and get instant risk predictions:

| Risk Rating | Meaning |
|-------------|---------|
| 🟢 **Positive** | Low risk, financially healthy |
| 🟡 **Neutral** | Moderate risk, stable |
| 🔴 **Negative** | High risk, potential default |
| 🟣 **Future Default** | Very likely to default |

## 📁 Required CSV Format

Your CSV must contain these columns for each year (2023, 2024, 2025):

**Balance Sheet:**
- `Cash & Equivalents_YYYY`
- `Accounts Receivable_YYYY`
- `Inventory_YYYY`
- `Prepaid Expenses_YYYY`
- `Total Current Assets_YYYY`
- `Property, Plant & Equipment_YYYY`
- `Intangible Assets_YYYY`
- `Goodwill_YYYY`
- `Long-term Investments_YYYY`
- `Total Non-Current Assets_YYYY`
- `TOTAL ASSETS_YYYY`
- `Accounts Payable_YYYY`
- `Short-term Debt_YYYY`
- `Accrued Expenses_YYYY`
- `Current Portion of Long-term Debt_YYYY`
- `Total Current Liabilities_YYYY`
- `Long-term Debt_YYYY`
- `Deferred Tax Liabilities_YYYY`
- `Pension Obligations_YYYY`
- `Total Non-Current Liabilities_YYYY`
- `TOTAL LIABILITIES_YYYY`
- `Common Stock_YYYY`
- `Additional Paid-in Capital_YYYY`
- `Retained Earnings_YYYY`
- `Treasury Stock_YYYY`
- `Other Comprehensive Income_YYYY`
- `TOTAL EQUITY_YYYY`

**Income Statement:**
- `Revenue_YYYY`
- `Cost of Goods Sold_YYYY`
- `Gross Profit_YYYY`
- `Selling, General & Administrative_YYYY`
- `Research & Development_YYYY`
- `Depreciation & Amortization_YYYY`
- `Operating Income (EBIT)_YYYY`
- `Interest Income_YYYY`
- `Interest Expense_YYYY`
- `Net Interest Income_YYYY`
- `Other Income (Expense)_YYYY`
- `Pre-tax Income (EBT)_YYYY`
- `Income Tax Expense_YYYY`
- `Net Income_YYYY`
- `EBITDA_YYYY`

**Required:**
- `Customer Name` (company identifier)

> Replace `YYYY` with `2023`, `2024`, `2025`

## 🚀 How to Deploy Your Own Copy

### Step 1: Create GitHub Repository
1. Go to [github.com](https://github.com) and sign in
2. Click **+** → **New repository**
3. Name: `default-risk-predictor`
4. Visibility: **Public**
5. Check **Add a README file**
6. Click **Create repository**

### Step 2: Upload Files
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop `index.html` from this folder
3. Click **Commit changes**

### Step 3: Enable GitHub Pages
1. Go to **Settings** tab
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: `main`, Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Live URL
- Wait 1-2 minutes for deployment
- Your app will be at: `https://YOUR_USERNAME.github.io/default-risk-predictor`
- Replace `YOUR_USERNAME` with your actual GitHub username

## 🛠️ Local Development

Simply open `index.html` in any web browser:
```bash
# On macOS
open index.html

# On Windows
start index.html

# On Linux
xdg-open index.html
```

Or use VS Code Live Server extension for hot reload.

## 📜 License

This project is for educational and analytical purposes.
