# MATKA CLUB V28

MongoDB-backed V28 build.

## Run
1. Install Node.js dependencies: `npm install`
2. Set `MONGODB_URI` to your MongoDB connection string.
3. Optional: set `MONGODB_DB=matka_club` and `PORT=3000`.
4. Start: `npm start`
5. Open: `http://localhost:3000`

The application stores users, results, coin balances, requests, transactions, login history and prediction records in MongoDB. Prediction records use non-redeemable points only and do not deduct or pay out coins.
