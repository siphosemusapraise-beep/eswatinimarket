ESWATINIMARKET — PHOTO & VIDEO LISTING PROTOTYPE

Files:
- index.html: app interface and client-side logic
- manifest.json: installable web app settings
- service-worker.js: basic offline cache
- icon-192.png and icon-512.png: app icons

Features in this prototype:
- Create listings with photos or videos selected from a phone
- Product name, brand, price in SZL, condition, category and stock
- Seller/shop name and phone/WhatsApp contact field
- Location/town, delivery/collection choices and delivery fee
- Search product name, brand, seller, location, category and description
- Newest listings are shown first when browsing
- Private chat button opens a one-to-one WhatsApp conversation with the seller when their phone number is provided
- My posts, delete local demo posts, cart and cash order form

IMPORTANT LIMITATIONS:
This is a local prototype. Posts and media are saved in this browser on this device only; they do not become public or sync to other users. Private chat opens WhatsApp; it is not an in-app chat system. The example listings do not have phone numbers, so private chat works only on listings where a seller supplies a valid WhatsApp number. Demo orders are not sent to sellers and no payment is processed. Local browser storage may be cleared or run out of space. Do not use this prototype for real orders or sensitive customer data.

To launch the prototype using only a Samsung Android phone:
1. Extract the ZIP in My Files.
2. Open github.com in Chrome and create a repository.
3. Upload index.html, manifest.json, service-worker.js, icon-192.png and icon-512.png to the repository root.
4. Repository Settings > Pages > deploy from branch > main > /(root) > Save.
5. Wait for the HTTPS Pages URL. Open it in Chrome.
6. Chrome menu > Install app or Add to Home screen.

To launch a real multi-user marketplace:
- Add user registration/login and seller verification.
- Store listings and media in secure shared database/object storage, not localStorage.
- Build in-app private messaging with access rules so only buyer and seller can read each conversation.
- Add moderation/reporting, privacy policy, terms, backups and data deletion controls.
- Add server-created orders, seller notifications and order status tracking.
- Establish delivery coverage and fee rules across Eswatini.
