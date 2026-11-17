# Dealer Expenses & Stock — Demonstration

This is a static, responsive demonstration intended for a dealer presentation.

## Run locally
Open `index.html` in a modern browser, or use the VS Code Live Server extension.

## Demo access
- Administrator: username `admin`, password `admin123`
- The Administrator can create additional supervisor accounts from Team management.

## Included
- Responsive desktop and mobile layout
- Overview dashboard
- Starts with empty expense and stock records
- Supervisor can record and confirm stock receipts; Administrator can review them
- Administrator can create demo supervisor accounts and share their credentials manually
- Supervisors see only expense and stock records they created; Administrator can review all records
- Monthly filters and summaries
- CSV exports

## Important limitations
- This is a demonstration, not a production business system.
- Changes are stored in browser localStorage on the current device only; the Administrator can see the Supervisor's records only in that same browser.
- Created supervisor accounts and passwords are stored in localStorage and work only in the same browser.
- Supervisor passwords are stored as plain text for this demo and are not secure credentials.
- Record visibility is a demo UI filter, not secure server-side authorization.
- Data is not shared between users or devices.
- Demo passwords are not secure authentication.
- Do not enter real customer, employee, financial, stock, or business information.
- Do not use this version for actual business operations.

GitHub Pages is suitable only for publishing this static presentation/demo subject to GitHub's current usage policies. A real shared system requires secure production hosting, authentication, a database, and server-side authorization.
