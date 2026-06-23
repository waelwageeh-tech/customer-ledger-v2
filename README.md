# customer-ledger-v2

A modern, offline-first customer ledger application for managing sales, payments, and customer transactions.

## Features

✨ **Core Functionality**
- Add, edit, and delete customers
- Track sales transactions with weight and pricing
- Record payments with multiple methods (Cash, Vodafone Cash, InstaPay)
- View running balance per customer
- Search across all customer data

📊 **Reporting & Export**
- Export transactions to Excel (CSV)
- Export transactions to PDF with formatted statements
- Global audit reports for all payments
- Date range filtering

💾 **Data Management**
- Offline-first: All data stored locally in your browser
- Auto & manual backup to JSON files
- System restore from backup files
- No server required, no internet needed

🎨 **Design**
- Dark mode iOS-style interface
- Mobile-optimized responsive design
- Touch-friendly buttons and inputs

## Quick Start

1. Open the app: [Customer Ledger v1](https://waelwageeh-tech.github.io/customer-ledger-v2/)
2. Click **+ Add** to create your first customer
3. Click on any customer to add transactions
4. Use **Export** to download reports

## Usage

### Adding a Customer
1. Click **+ Add** button
2. Fill in customer details (name, mobile, shop info)
3. Click **Save Customer**

### Recording Transactions
1. Open a customer profile
2. Click **+ Add Transaction**
3. Choose transaction type:
   - **Sell**: Enter weight and price/kg
   - **Payment**: Enter amount and payment method

### Exporting Data
1. Click **Export** in customer profile
2. Choose Excel (CSV) or PDF format
3. Select optional date range
4. Download or share the file

### Backup & Restore
- **System Hub** → **Manual Backup**: Download all data as JSON
- **System Hub** → **Restore System**: Upload a previously saved backup

## Technology

- Pure HTML5, CSS3, and JavaScript
- LocalStorage for data persistence
- jsPDF and html2canvas for PDF generation
- No dependencies or build tools required

## Browser Support

Works on all modern browsers:
- ✅ Chrome/Edge
- ✅ Firefox
- ✅ Safari (iOS & macOS)
- ✅ Opera

## Privacy

All your data stays on your device. Nothing is sent to servers. You have full control.

---

**Version**: 1.0  
**Author**: waelwageeh-tech  
**License**: MIT
