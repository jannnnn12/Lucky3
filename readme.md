# Enhanced Queue Management System — UI Prototype

What this is
- A lightweight front-end prototype for:
  - Kiosk (ticket issuance) — kiosk.html
  - Display panel (live queue display) — display.html
  - Admin dashboard (call / skip / recall / service history) — admin-dashboard.html
- Uses browser localStorage as a simple datastore to simulate your JSON database and flow.
- Services included: GSIS, SSS, Senior Loan.

How to run
- Download all files to a single folder.
- Open `index.html` in your browser (Chrome/Edge/Firefox).
- Use the Kiosk page to issue tickets. Then open Display and Admin pages (can be separate browser windows) to see interactions.
- No server required.

Files
- index.html — simple landing with links to each UI page.
- kiosk.html — kiosk UI to issue queue numbers and optionally capture client account info.
- display.html — TV/monitor display panel showing current and next numbers and service type; supports TTS announcements.
- admin-dashboard.html — admin controls to call, skip, recall; view service history; edit queue entries.
- style.css — shared styles.

Notes
- This is a prototype for demonstration and UI testing only. Replace localStorage operations with API calls to your backend (the JSON database / endpoints) in production.
- Audio uses the Web Speech API (TTS). Chrome provides good support.
- Ticket numbering uses prefix L3- and numeric increment persisted in localStorage.

Next steps I can take for you: convert this prototype to React/Vue, wire it to your JSON backend or MongoDB seed, or produce high-fidelity Figma mockups. I created the prototype and seeded the UI with the GSIS / SSS / Senior Loan services so you can interact with the flows now.