# Swadeshi Tourism Hub 🇮🇳 — SIH Prototype

A clickable, single-file prototype built for **Smart India Hackathon (SIH)**, demonstrating a **Smart Tourism & Safety Platform** for domestic travelers in India. It showcases both the mobile app experience and a companion web dashboard (for tourism boards / admins) in one interactive HTML demo.

> ⚠️ This is a **UI/UX prototype** — a front-end mockup built to pitch and demo the idea, not a production application. There's no backend, database, or real API integration; all data (itineraries, guides, products) is hardcoded for demonstration purposes.

## Problem Statement (context)

Built around the theme of boosting domestic tourism through technology — helping travelers discover destinations, plan trips, access local experiences, and stay safe, while giving tourism authorities visibility into tourist activity and hotspots.

## What's in the prototype

### 📱 Mobile App View
- **Splash & Login** — branded onboarding screens
- **Home Dashboard** — quick access to core features
- **AI Itinerary Planner** — pick trip duration, budget, and interests (Eco Tourism, Cultural, Adventure, Food) and generate a sample day-by-day itinerary with estimated cost
- **SOS Safety** — one-tap emergency button with quick-dial info for Police (100), Ambulance (108), Fire Brigade (101), and live location
- **Local Marketplace** — buy local handicrafts, homestays, folk events, textiles, organic produce, and art directly from local artisans/communities
- **Tour Guide Profiles** — blockchain-verified guide profiles with ratings, tour count, and languages spoken
- **Virtual Tours** — VR/immersive preview screen for destinations

### 💻 Web Dashboard View
- Tourism analytics dashboard with stat cards (visitor counts, etc.)
- Chart section for visualizing tourism trends
- Popular destinations list with visit counts

Both views are togglable from a single **Mobile / Web** switch in the top-right corner of the page.

## Tech stack

Pure front-end demo — no frameworks, no build step:
- **HTML5**
- **CSS3** (gradients, flexbox/grid, animations — all embedded in `index.html`)
- **Vanilla JavaScript** (screen navigation, chip selection, itinerary generation, SOS trigger — all embedded in `index.html`)

## Running it

No installation needed — it's a static HTML file.

```bash
git clone https://github.com/Dhanush1756/prototype_sih.git
cd prototype_sih
```

Then just open `index.html` in any browser (double-click it, or run a quick local server):

```bash
python -m http.server 8000
# visit http://localhost:8000
```

## How to navigate the demo

1. Use the **View Mode** toggle (top-right) to switch between **📱 Mobile** and **💻 Web**.
2. On the mobile view, start at the splash screen → tap **Login** → explore the Home screen's four quick options (AI Itinerary, Virtual Tours, Marketplace, SOS Safety).
3. In **AI Itinerary**, select interests and click **Generate Itinerary** to see a sample cultural heritage tour appear.
4. In **SOS Safety**, click the pulsing SOS button to see the emergency trigger in action.

## Project structure

```
prototype_sih/
└── index.html    # Entire prototype — markup, styles, and interaction logic
```

## Roadmap / next steps (for future development beyond the prototype)
- [ ] Real backend + database for itineraries, marketplace listings, and guide bookings
- [ ] Actual AI/ML-based itinerary recommendation engine
- [ ] Real-time SOS integration with location sharing to authorities
- [ ] Blockchain-based guide verification (currently just a UI badge)
- [ ] Payment gateway integration for marketplace purchases
- [ ] Split into modular components (currently a single HTML file)

