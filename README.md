# FinTrack — Browser-Only Version

FinTrack is a static personal finance management application. It runs directly in the browser and stores account, settings, savings, investments, protection, transactions, and other app data in the browser's `localStorage`.

## Deployment

This version does not require PostgreSQL, Neon, API routes, server functions, or environment variables.

### GitHub + Vercel
1. Upload the contents of this folder to your GitHub repository.
2. Import the repository into Vercel.
3. Deploy it as a static site.
4. No database connection is required.

## Important data behavior

- Data is stored locally in the browser on the device being used.
- Data does **not** automatically sync between phone, tablet, and computer.
- Clearing browser/site data can remove locally stored data.
- Use **Settings → Backup & reset → Export Backup** regularly.
- Use **Import Backup** to restore an exported JSON backup in another browser/device.

## Default administrator

Email: `admin@fintrack.local`
Password: `admin1`

Change the password after signing in if needed.

## Mobile

The application is designed to work on desktop and mobile browsers. Savings and investment records are stored locally in the same browser storage used by the rest of the application.
