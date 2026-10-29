# MDPL Season 5 · Player Auction

A single-page auction site: an auctioneer console and a big screen for the projector.

- `index.html`: the whole site (players, photos, logos and sounds are built in)
- `firestore.rules`: database security rules. Paste into Firebase → Firestore → Rules → Publish.
- `vercel.json`: hosting settings (`/big` opens the big screen)

## Links
- Console: `https://<your-site>/` (Google sign-in, listed auctioneers only)
- Big screen: `https://<your-site>/big` (anyone can watch)

## Who can run the auction
Listed in two places, kept in step: `window.MDPL_ADMINS` in `index.html` and the list in `firestore.rules`.
