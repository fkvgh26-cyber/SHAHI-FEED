# SHAHI AGRO FARM — Android app starter

A React Native / Expo starter for the SHAHI AGRO FARM grass silage ordering app.

## Included
- Plantify-inspired green-and-cream UI
- Home, Shop, Orders, Tracking, About and Settings screens
- SHAHI GRASS SILAGE: 50 kg per packet, ৳350 per packet
- Quantity rule: minimum 20 and maximum 400 packets
- Total weight and price calculation
- Customer name, phone and delivery address
- Cash on Delivery, bKash and Nagad payment selection
- Required transaction ID for digital payment requests
- Demo tracking code generation and lookup on the current device
- English/Bangla setting and light/dark appearance toggles

## Run it
1. Install Node.js LTS on a computer.
2. Install Expo Go on an Android phone.
3. Extract this ZIP and open a terminal inside this folder.
4. Run `npm install`
5. Run `npx expo start`
6. Scan the QR code with Expo Go (or use `npx expo start --android` with Android tooling installed).

## Important before real customers use it
This is a functional UI prototype, not a production payment system. Orders and tracking are held only in app memory and will not persist after the app closes. The app does not verify bKash/Nagad transaction IDs or charge payments. For production, connect a secure backend/database, admin order dashboard, authenticated payment verification or manual admin approval, and delivery tracking. Never trust a transaction ID alone as proof of payment. The app currently creates a demo order request and a local tracking code.

## Brand details used
- bKash merchant/contact number: 01799900886
- WhatsApp order confirmation contact: 01814026318
- Contact: 01632638470
- Address: Babul Chearman Bari, Char Bojlul Korim, Char Bata-3813, Subarnachar, Noakhali
