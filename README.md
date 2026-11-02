# 🌺 Bali Tropical Island Odyssey — December 2023 / January 2024

An elegant, high-fidelity, responsive static web application designed to plan, explore, and navigate your 10-day Bali journey from **December 23, 2023 to January 1, 2024**.

This dashboard is fully optimized for mobile devices, tablets, and laptops, featuring direct Google Maps route integrations, interactive packing checklists, stay payment trackers, and Balinese cultural guidelines.

---

## 🌟 Key Features

1. **Interactive Route Timeline (Days 1–10)**:
   - Day-by-day navigation across **Seminyak**, **Nusa Penida Island**, **Ubud**, and **Kuta**.
   - Direct one-click **"Launch Route on Google Maps"** button for each day.
   - Comprehensive stats for travel distances, transit / boat times, base areas, and highlight themes.
   - Region filter pills (`All Days`, `Seminyak`, `Nusa Penida`, `Ubud`, `Kuta`) and real-time instant search bar.

2. **Detailed Sightseeing Hyperlinks**:
   - Direct Google Maps search links and cultural background for every iconic attraction:
     - **Seminyak & South**: Uluwatu Temple, GWK Cultural Park, Pandawa Beach, Tanah Lot Sea Temple, Finns Beach Club Canggu, Seminyak Evening Market, Bollywood Masala Pure Veg Restaurant.
     - **Nusa Penida Island**: Sanur Port Speedboat crossing, Broken Beach (Pasih Uug), Kelingking Beach (T-Rex Headland), Crystal Bay snorkeling.
     - **Ubud & Highlands**: Ubud Royal Palace, Ubud Art Market, Lempuyang Temple (Gates of Heaven), Tirta Gangga Water Palace, Besakih Mother Temple, Alas Harum Rice Terraces & Swings, Ulun Danu Beratan Floating Temple, Sacred Monkey Forest Sanctuary, Goa Gajah (Elephant Cave).
     - **Kuta**: Sulis Beach Hotel & Spa recovery, Kuta Beach golden sunset, Beachwalk open-air bazaar.

3. **Interactive Bali Packing Checklist**:
   - 25 essential items categorized across 5 crucial island sectors:
     - 📋 *Official Documents & Formalities* (Passport validity, Indonesia e-VOA, e-CD customs declaration QR, Bali Tourist Levy, IDP).
     - 🩳 *Tropical Wear & Island Gear* (Breathable linen, swimwear, UV rashguard, sunglasses, water shoes).
     - 🥻 *Sacred Temple Attire & Etiquette* (Balinese sarongs, selendang sash, modest tops, small cash).
     - 📱 *Island Electronics & Marine Protection* (Universal Type C/F adapters, 20,000mAh power bank, waterproof phone pouches, action cam).
     - 💊 *Health, Skin Care & Island Essentials* (Reef-safe SPF 50+, Soffell mosquito repellent, ORS electrolytes, travel medicine).
   - Real-time packing progress bar with **automatic local storage persistence**.

4. **Interactive SVG Island Map**:
   - Vector map of Bali and Nusa Penida highlighting regional hubs, Mount Agung volcano, speedboat routes, and interactive clickable destination pins that jump straight to that day's itinerary.
   - Tropical climate and weather insights for December/January.

5. **Accommodations & Payment Tracker**:
   - Explicit tracking for all booked stays:
     - 🏡 **Kubudtuma Villas** (Seminyak, Dec 23–26) — `PAID ✅`
     - 🏝️ **Permata Hills** (Nusa Penida, Dec 26–27) — `PAID ✅`
     - 🌿 **Gajahbiru Bungalows** (Ubud, Dec 28–31) — `PAY AT PROPERTY 💵`
     - 🎆 **New Year's Eve 2024 Celebration** (Dec 31) — `NO HOTEL / PARTY 🎊`
     - 🌊 **Sulis Beach Hotel and Spa** (Kuta, Jan 01) — `BOOKED & RELAX 🏖️`

6. **Pure Veg Dining & Island Logistics**:
   - Highlighted Indian vegetarian dining at **Bollywood Masala Pure Veg Restaurant** (Seminyak) and organic vegan dining spots in Ubud.
   - Speedboat tips for the Sanur Harbor terminal.
   - Ride-hailing guidelines (Grab/Gojek vs Bluebird vs private drivers).
   - Balinese temple customs (*Canang Sari* offerings and dress codes).

---

## 🗺️ Itinerary Overview

| Day | Date | Base Region | Key Highlights | Night Stay & Status |
| :---: | :---: | :---: | :--- | :--- |
| **Day 1** | Dec 23, 2023 | Seminyak | DPS Airport arrival, Seminyak Night Market, Bollywood Masala Pure Veg Restaurant | Kubudtuma Villas (`PAID`) |
| **Day 2** | Dec 24, 2023 | Seminyak / South | Uluwatu Cliff Temple, Garuda Wisnu Kencana (GWK), Pandawa Beach | Kubudtuma Villas (`PAID`) |
| **Day 3** | Dec 25, 2023 | Seminyak / West | Tanah Lot offshore sea temple, Finns Beach Club Canggu, Nusa Penida prep | Kubudtuma Villas (`PAID`) |
| **Day 4** | Dec 26, 2023 | Nusa Penida | Sanur Port speedboat, Broken Beach (Pasih Uug), Kelingking T-Rex Cliff | Permata Hills (`PAID`) |
| **Day 5** | Dec 27, 2023 | Nusa Penida ➔ Ubud | Crystal Bay snorkeling & reef relaxation, speedboat to mainland, Ubud transfer | Heading to Ubud |
| **Day 6** | Dec 28, 2023 | Ubud | Gajahbiru Bungalows check-in, Ubud Royal Palace, Ubud Art Market | Gajahbiru Bungalows (`PAY AT PROPERTY`) |
| **Day 7** | Dec 29, 2023 | East Bali | Pura Lempuyang (Gates of Heaven), Tirta Gangga Water Palace, Besakih Mother Temple | Gajahbiru Bungalows (`PAY AT PROPERTY`) |
| **Day 8** | Dec 30, 2023 | Central & North | Alas Harum Rice Terrace swings, Ulun Danu Beratan floating lake temple | Gajahbiru Bungalows (`PAY AT PROPERTY`) |
| **Day 9** | Dec 31, 2023 | Ubud & NYE | Sacred Monkey Forest Sanctuary, Goa Gajah Elephant Cave, New Year's Eve Countdown | No Hotel (`ALL-NIGHT NYE CELEBRATION`) |
| **Day 10** | Jan 01, 2024 | Kuta | Sulis Beach Hotel and Spa check-in, Balinese spa recovery, Kuta Beach sunset walk | Sulis Beach Hotel and Spa (`BOOKED`) |

---

## 🚀 Running Locally

To run and preview the dashboard locally:

```bash
# Navigate to the project directory
cd /path/to/bali_trip

# Start a lightweight local HTTP server (Python 3)
python3 -m http.server 8080

# Open in your browser:
# http://localhost:8080
```

Alternatively, you can double-click and open `index.html` directly in any modern web browser.

---

## 📱 Mobile Friendly & Offline Ready

The application uses native CSS Grid & Flexbox, smooth touch scrolling, and client-side JavaScript with zero heavy dependencies or frameworks, making it ultra-fast and lightweight to run smoothly even on limited mobile data connections while traveling.
