# Uday Udyam — Grain Trading Ledger

A simple billing and inventory app for a grain trading business — record purchases from farmers, sales to traders, track stock by grain/grade/godown, and print bills.

## Use it
Just open `index.html` in any browser, or visit it live once published on GitHub Pages. Once published, an **Install App** button appears in the app — tap it to install Uday Udyam like a regular app on your phone or laptop (no app store needed).

Upload all of these files together to the same folder in your repo:
- `index.html`
- `manifest.json`
- `sw.js`
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`

All data is stored privately in your own browser (`localStorage`) — nothing is sent to a server. This also means:
- Data does **not** sync between devices or browsers automatically.
- Clearing your browser data will erase it. Consider noting down important totals elsewhere occasionally.

## Features
- Purchase bills (farmer → you), with bags, weight, extra loose kg, rate, labour and other deductions
- Sale bills (you → trader/buyer), drawing down from stock batches
- Inventory tracked by grain, grade, and godown
- Printable invoices with your business name and GST number
- Add your own grain types and godowns anytime from Settings
