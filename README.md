# MATKA CLUB V30

Mobile-first results dashboard with SUPERADMIN / ADMIN / USER roles and MongoDB-backed state.

## V30 additions
- Superadmin analytics and operational overview
- Result history and audit log
- Admin search/filter and activity view
- User search/filter
- User notifications with read/unread state
- Profile and password change
- Login/security audit events
- Existing SUPERADMIN-only result publishing preserved
- Prediction points remain non-redeemable and are not deducted from coin balance

## Run
1. `npm install`
2. Set `MONGODB_URI` or `MONGO_URI` to the intended MongoDB Atlas connection.
3. Optional: set `MONGODB_DB` (default `matka_club`).
4. `npm start`

No real-money betting, payments, deposits, withdrawals, cash-out, or wagering functionality is included.
