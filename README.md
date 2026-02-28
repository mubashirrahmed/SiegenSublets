# Siegen Sublet (MVP)

## Setup
1) npm install
2) Copy `.env.local.example` -> `.env.local` and fill Firebase keys.
3) Firebase Console:
   - Enable Auth providers: Google + Phone
   - Enable Firestore + Storage
   - Apply rules from `firebase.rules.firestore` and `firebase.rules.storage`

## Run
npm run dev
