# Ike's Money Manager

A mobile-friendly personal and business finance tracker.

## Current features
- Dashboard with total balance, monthly income, expenses and net
- Separate balances for MTN MoMo, GCB Bank and Payoneer
- Record income, expenses and transfers between accounts
- Personal and business categories (including custom-use categories)
- Transaction history and monthly category report
- Export full JSON backup or transactions CSV; restore a JSON backup
- Browser-local storage and basic offline support after first visit

## Important data notes
This first version stores records in the browser on the device where you use it. It does not automatically sync with a bank, MTN MoMo or Payoneer, and it does not sync between devices. Export backups regularly. Do not enter banking passwords, PINs or one-time codes. Payoneer is tracked as a manually entered Ghana-cedi equivalent in this version.

## Run it
Open `index.html` in a browser, or enable GitHub Pages for this repository and visit the Pages URL. For offline/PWA features, use the hosted HTTPS version and open it once while online.

## Planned next
- Validate official, permitted data-import options for supported financial providers
- Improve recurring transactions, account currencies and reporting
- Add safer cloud backup/synchronization only with explicit authentication and privacy controls
