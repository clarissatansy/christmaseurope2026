# PRD — Trip site update: flights, budget page, Strasbourg + Frankfurt extension

**Status:** Spec only — do not build yet.
**Last updated:** 2026-09-10 (revised with user answers)
**Applies to:** the `christmaseurope2026` site (Munich → Lucerne Christmas trip) and its ["December Timetable" brainstorm artifact](https://claude.ai/code/artifact/d49f9ed3-8ded-484a-ab15-5e3b952f46ae).

---

## 1. What this update covers

1. Record the **real flight bookings** for both travellers (Irvin from Singapore, Clar from Philadelphia).
2. Replace the "fly home from Zurich" ending with a new tail: **Strasbourg (day) → Frankfurt (rest of trip) → fly home from Frankfurt.**
3. Add a **Budget** page (separate page, not an in-page section).
4. Add a **Day-by-day itinerary** page (separate page), based on the "December Timetable" artifact.
5. Add **Strasbourg** and **Frankfurt** as cities on the main page, with Frankfurt accommodation options.

All decisions from the review round are folded in. Smaller remaining confirmations are in **§7**.

---

## 2. Travellers & flights

Both fly **into Munich (MUC)** around midday **Fri Dec 18**, and both fly **home from Frankfurt (FRA)** on **Wed Jan 6**.

### 2.1 Clar — Philadelphia
Multi-city, Economy, 1 passenger — **USD $1,089** ("lowest total price", Google Flights).

| Leg | Date | Routing | Airline / flight | Aircraft | Time | Notes |
|---|---|---|---|---|---|---|
| Outbound 1 | Thu Dec 17 | PHL 18:35 → LHR 06:35 (+1) | British Airways **BA 66** | A350 | 7h, overnight | "Often delayed 30+ min" |
| Layover | | London **LHR**, 2h 15m | | | | |
| Outbound 2 | Fri Dec 18 | LHR 08:50 → MUC 11:50 | British Airways **BA 946** | A320neo | 2h | Below-avg legroom (29") |
| Return 1 | Wed Jan 6 | FRA 10:40 → ATL 15:10 | Delta **DL 15** | A330 | 10h 30m | |
| Layover | | Atlanta **ATL**, 3h 30m | | | | |
| Return 2 | Wed Jan 6 | ATL 18:40 → PHL 20:37 | Delta **DL 2065** | A321 | 1h 57m | "Often delayed 30+ min" |

Emissions (Google Flights estimate): outbound 426 kg CO2e (−12%); return 610 kg CO2e (+40%).

### 2.2 Irvin — Singapore
Emirates via Dubai, Economy — **SGD 1,394**.

| Leg | Date | Routing | Airline / flight | Aircraft | Time |
|---|---|---|---|---|---|
| Outbound 1 | Fri Dec 18 | SIN 00:30 → DXB 04:10 | Emirates **EK 353** | A380 | 7h 40m |
| Layover | | Dubai **DXB**, 4h 30m | | | |
| Outbound 2 | Fri Dec 18 | DXB 08:40 → MUC 12:30 | Emirates **EK 49** | A380 | 6h 50m |
| Return 1 | Wed Jan 6 | FRA 09:40 → DXB 19:00 | Emirates **EK 44** | B777 | 6h 20m |
| Layover | | Dubai **DXB**, 2h 0m | | | |
| Return 2 | Wed Jan 6 | DXB 21:00 → SIN 08:30 (+1, Thu Jan 7) | Emirates **EK 314** | B777 | 7h 30m |

**Resolved:** Irvin's return is **Wed Jan 6** (arriving Singapore Thu Jan 7). The earlier "to 5 Jan" note in the brief is superseded. Both travellers now have identical trip nights.

---

## 3. Revised route & itinerary

### 3.1 City sequence (updated)

```
Munich → Nuremberg → Prague → Vienna → [ÖBB Nightjet sleeper] → Zurich → Lucerne → Strasbourg (day) → Frankfurt → fly home
   in: MUC (both, Fri Dec 18)                                                                           out: FRA (both, Wed Jan 6)
```

**Removed:** the "Zurich again (Jan 2–3)" leg and "fly home from Zurich". Zurich stays as a mid-trip stop (Dec 28–30, including the Grindelwald / Interlaken / Lauterbrunnen day trip).

### 3.2 Nights (updated — both travellers identical)

| City | Dates | Nights |
|---|---|---|
| Munich | Dec 18–20 | 2 |
| Nuremberg | Dec 20–22 | 2 |
| Prague | Dec 22–25 | 3 |
| Vienna | Dec 25–27 | 2 |
| Nightjet sleeper (Vienna → Zurich) | Dec 27 night | 1 |
| Zurich | Dec 28–30 | 2 |
| Lucerne | Dec 30 – Jan 3 | **4** (was 3) |
| Strasbourg | Jan 3 | 0 (day visit, no overnight) |
| Frankfurt | Jan 3 – Jan 6 | **3** |
| **Total** | **Dec 18 → Jan 6** | **19 nights** |

Lucerne's 4th night is the old "Zurich again" night folding back in. The Munich→Lucerne portion is otherwise **settled** and matches the artifact.

### 3.3 New tail — Jan 3 onward

> Brief: *"3 Jan will be Strasbourg and then we will take a train to Frankfurt … Frankfurt where we will spend the rest of the trip."* **No overnight in Strasbourg** (confirmed).

**Jan 3 (Sat) — Lucerne → Strasbourg (day) → Frankfurt**
- Check out of Lucerne. Train **Lucerne → Basel SBB** (~1h), then **Basel → Strasbourg** (~30–75 min; regional TER, or a TGV which needs a paid seat reservation). Left-luggage at Strasbourg station.
- **Strasbourg — day visit:**
  - **Strasbourg Cathedral (Cathédrale Notre-Dame)** — Gothic façade, the astronomical clock, and the platform/tower climb for the view over the Grande Île.
  - **La Petite France** — the canal-and-timber-house quarter, locks, the Ponts Couverts and the Barrage Vauban terrace.
  - **Parc de l'Orangerie** — Strasbourg's oldest park, near the European institutions: lake, stork enclosure, Joséphine pavilion — a quieter walk to close the visit.
  - Alsatian lunch somewhere in between (tarte flambée / choucroute / baeckeoffe).
  - ⚠️ Strasbourg's Christkindelsmärik ends **Dec 24** (2026: ~Nov 26 – Dec 24). By Jan 3 it is over — this is a cathedral-and-old-town stop, **not** a market stop.
- Evening: train **Strasbourg → Frankfurt** (~1h50m direct ICE; some services need a change; reservation may be required). Arrive Frankfurt Jan 3 night.

**Jan 3–6 — Frankfurt** (3 nights, both travellers)
- **Bahnhofsviertel** — the station quarter right by the hotels: one of the city's densest eating-and-drinking districts, gritty and diverse; base for evenings.
- **Höchst** — the half-timbered old town on the western edge of Frankfurt (Höchst Castle, Justinuskirche, the porcelain manufactory), a short S-Bahn ride out; a calmer half-day.
- **Stadtwald (Frankfurt City Forest)** — large forest on the south side for a walk (Goetheturm lookout tower, forest paths); pairs with a relaxed afternoon.
- **Chinaski Tagesbar** — daytime café-bar for coffee / a light stop.
- **Berbere at African Queen** — Eritrean/Ethiopian restaurant; a dinner option.
- **Oosten** — restaurant on the Main riverfront (Osthafen side); dinner / drinks with the water view.
- Slack time for the classic core if wanted: Römerberg & the reconstructed Altstadt, Kaiserdom, the Museumsufer (Städel, Senckenberg), Kleinmarkthalle.
- ⚠️ Frankfurt's Christmas market ends **Dec 22** — closed by January. Post-Christmas city stop.
- ✅ **Jan 6 (Epiphany) is *not* a public holiday in Hesse** — Frankfurt operates normally on the departure day. (Bavaria, Baden-Württemberg and Saxony-Anhalt observe it; Hesse does not. Verify at build.)
- Both fly out **FRA on Wed Jan 6** — Irvin 09:40 (early check-out), Clar 10:40.

**Countries touched:** now **5** — Germany, Czechia, Austria, Switzerland, **France** (Strasbourg / Alsace).

---

## 4. New page — **Budget**

**Scope:** combined cost for **two people**. Accommodation is **one shared room** for the two of them, so night costs are per-room (not doubled).
**Base currency:** USD.
**FX rate:** **SGD → USD = 0.7911** (xe.com mid-market, 2026-09-10). Show the rate and date on the page. → Irvin's **SGD 1,394 ≈ USD $1,103**.

| # | Item | Amount (USD) | Status | Notes |
|---|---|---|---|---|
| 1 | **Flight — Clar** (PHL⇄, BA + Delta, multi-city, Economy) | **$1,089** | Quoted | Dec 17 dep / Jan 6 return; into MUC, out of FRA |
| 2 | **Flight — Irvin** (SIN⇄, Emirates via DXB, Economy) | **SGD 1,394 = $1,103** | Quoted | @ 0.7911 SGD→USD (xe.com mid-market, 2026-09-10) |
| — | *Flights subtotal* | **$2,192** | | |
| 3 | **Rail — Interrail Global Pass, 15 days continuous, 2nd class, adult × 2** | **$566 × 2 = $1,132** | Quoted | **Continuous** pass (see §4.1). No rail travel on the first 2 / last 3 days, so a 15-day continuous window covers every travel day. |
| — | *Known subtotal (flights + rail passes)* | **$3,324** | | The firm number to show up top |
| 4 | **Rail — seat & sleeper reservations** (extra, not covered by the pass) | **~$300–600** (2 pax) | Buffer | Nightjet Vienna→Zurich compartment (~€30–60 pp) + Railjet / ICE / TGV / EC seat reservations incl. the French trains via Basel. |
| 5 | **Accommodation** — 19 nights, **1 shared room**, not yet booked | **~$2,400–3,400** | Buffer | Mid-range from options already researched. Zurich (~$250/night) and Lucerne (~$240/night) are the expensive stretches; Frankfurt (Jan 3–6) not yet priced — 3 Agoda options in §6.3. |
| 6 | **Attractions / activity tickets** (2 pax) | **TBD** | TBD | Mt Titlis, Rigi + Kaltbad spa, Grindelwald day trip, Bratislava, BMW Museum, Dachau, Prague & Vienna museums, Lake Lucerne cruise, etc. Links already gathered for most cities. |
| 7 | **Food & daily spending** (2 pax) | **TBD** | TBD | — |

**Estimated all-in so far (excl. activities & food): ≈ USD $6,000–7,300** for two.

### 4.1 Interrail pass — continuous, validity window

- Product: **Interrail Global Pass — 15 days continuous**, 2nd class, adult; **2 passes** (one each).
- No rail travel on the **first 2 days** (Dec 18 arrival + Dec 19 in Munich) or the **last 3 days** (Jan 4–6 in Frankfurt / flying out), so the continuous window doesn't need to span the whole ~19-day trip.
- **Suggested activation: Sat Dec 20** (first train, Munich → Nuremberg). Day 1 = Dec 20 → Day 15 = **Jan 3**, which still covers the Lucerne → Basel → Strasbourg → Frankfurt travel day. Every rail day is inside the window:
  - Dec 20 Munich→Nuremberg · Dec 22 Nuremberg→Prague · Dec 25 Prague→Vienna · Dec 27→28 Nightjet Vienna→Zurich · Dec 28 Grindelwald day trip · Dec 30 Zurich→Lucerne · Lucerne day trips · **Jan 3 Lucerne→Strasbourg→Frankfurt**.
- Note on the page: reservations (item 4) are separate and mandatory on the Nightjet and most high-speed / French trains.

**Presentation notes for the build:**
- Status pill per row: *Quoted* / *Buffer* / *TBD*.
- Show the firm "known subtotal ($3,324)" prominently, with the estimated all-in range below it.
- Link each flight row to its booking; link the Interrail row to the pass product page.
- State the FX rate + date inline next to Irvin's flight figure.

---

## 5. New page — **Day-by-day itinerary**

- **Separate page.** Reuse the **structure of the "December Timetable" artifact** — day rows grouped by city, inline flags for closures / holidays / uncertainty; IBM Plex fonts, departures-board strip layout, light/dark tokens.
- **Settled (lift from the artifact, Dec 18 – Jan 2):** Munich → Nuremberg → Prague → Vienna → Nightjet → Zurich → Lucerne, including: Prague Castle on Dec 23 (closed Dec 24), Bratislava day trip Dec 26, Grindelwald / Interlaken / Lauterbrunnen day trip from Zurich Dec 28, Mt Titlis on Dec 30 (Pilatus cogwheel closed for winter — Kriens cable car alternative), Rigi + Kaltbad spa on Jan 1 (**still unconfirmed** for that date — keep the ⚠️ callout), Berchtoldstag Jan 2 (public holiday in Lucerne & Zurich cantons).
- **Extend Lucerne** by one night — now **Dec 30 – Jan 3**. Jan 2 stays a Lucerne day; add a Jan 3 morning checkout.
- **Add the new tail** from §3.3:
  - **Jan 3** — Lucerne → Basel → Strasbourg (Cathedral, La Petite France, Parc de l'Orangerie) → evening train → Frankfurt.
  - **Jan 3–6** — Frankfurt: Bahnhofsviertel, Höchst, Stadtwald, Chinaski Tagesbar, Berbere at African Queen, Oosten (+ optional Römerberg / Museumsufer / Kleinmarkthalle).
  - **Jan 6** — fly out FRA (Irvin 09:40, Clar 10:40).
- **Flags to carry:** Strasbourg market closed (ends Dec 24), Frankfurt market closed (ends Dec 22), Jan 6 not a Hesse holiday.
- Keep a "still unconfirmed" list: Rigi + Kaltbad spa Jan 1 operation, NYE fondue / winter cruise booking, exact Strasbourg⇄Frankfurt train (reservation need).

---

## 6. Main-page changes

### 6.1 Stats / hero / route
- **Countries:** 4 → **5** (add France).
- **Cities:** 6 → **8** (add Strasbourg, Frankfurt).
- **Nights:** → **19**.
- **Dates:** → **"December 18, 2026 – January 6, 2027"**.
- **Hero copy:** "meeting in Munich" stays; **"home from Zurich" → "home from Frankfurt"**. Add Strasbourg + Frankfurt to the route chips.
- **Route map:** extend the line past Lucerne → **Strasbourg** (west, via Basel) → **Frankfurt** (north). Two new markers; Strasbourg marked as a day stop.
- **Nav:** add links to the two new pages (**Budget**, **Itinerary**).

### 6.2 Flights table
Replace the four placeholder rows (PHL→MUC connecting / SIN→MUC nonstop / ZRH→PHL / ZRH→SIN) with the real bookings from **§2**. Both return legs are now **out of Frankfurt**. Keep the multi-city booking note. Optionally link to the Budget page.

### 6.3 New city sections

**Strasbourg** — Jan 3, **day visit, no overnight.**
- Framing: Alsatian old town after the markets have packed up.
- Highlights to feature: **Strasbourg Cathedral**, **La Petite France**, **Parc de l'Orangerie**.
- No accommodation card (day stop). Optionally note bag storage at Strasbourg station.

**Frankfurt** — **Jan 3–6, 3 nights** (both travellers).
- Framing: the wind-down — station-quarter food scene, the half-timbered Höchst old town, the city forest, and the Main riverfront. Markets closed by January; a base for the classic core if wanted.
- Highlights to feature: **Bahnhofsviertel**, **Höchst**, **Stadtwald**, **Chinaski Tagesbar**, **Berbere at African Queen**, **Oosten**.
- **Accommodation options** — price at build time with the same card treatment as other cities (image, per-night USD, link). Links are set to `checkIn=2027-01-03`, `los=3`, `currencyCode=USD`:
  1. **Toyoko Inn Frankfurt am Main Hauptbahnhof**
  2. **iPartment Frankfurt Bahnhofsviertel**
  3. **IntercityHotel Frankfurt Hauptbahnhof**
  > Use the **exact URLs the user supplied** (full query strings, affiliate `cid=1922889` / `tag=3a518944-36fd-49e2-a05d-91bfa4a414a6`) as the card links — verbatim, as with every other city.
  > ⚠️ **Occupancy:** the supplied links carry `adults=1`, but the trip is **2 people sharing one room**. Re-query these with **`adults=2`** (keeping `rooms=1`) when pricing the cards, so the per-night figure reflects the shared room. Flag to the user if a link then resolves to a different room type.

### 6.4 What stays the same
- The Nightjet section (Vienna → Zurich sleeper).
- All existing city sections and their accommodation / attraction cards for Munich, Nuremberg, Prague, Vienna, Zurich, Lucerne.
- The market-status table — but **add Strasbourg and Frankfurt** as **"closed — ends Dec 24 / ends Dec 22"**.

---

## 7. Confirmations — all resolved (2026-09-10)

1. **Interrail activation** — ✅ activate **only on leaving Munich** (Dec 20, first train). Days 1–2 (Dec 18–19) not covered by the pass.
2. **Reservation-fee buffer** — ✅ **$300–600 for two** kept as the placeholder.
3. **Accommodation buffer** — ✅ **$2,400–3,400** kept as the budget placeholder until priced.
4. **Frankfurt `adults=2` re-query** — ✅ re-run the 3 Agoda links at double occupancy for pricing; card URLs stay the user's originals.
5. **Trains** (Lucerne→Basel→Strasbourg; Strasbourg→Frankfurt) — ✅ leave exact services / reservations as "confirm when booking reservations".
6. **Two new pages** — ✅ standalone `budget.html` and `itinerary.html`, linked from the main nav, matching the site's styling.

**→ Approved to build.**

---

### Sources
- SGD→USD rate: [xe.com SGD/USD](https://www.xe.com/en-us/currencyconverter/convert/?Amount=1&From=SGD&To=USD) — 0.7911, 2026-09-10
- Strasbourg market dates: <https://ultimatechristmasmarkets.com/france/strasbourg-christmas-market/>
- Frankfurt market dates: <https://www.christmasmarketsgermany.com/frankfurt.php>
- Epiphany public-holiday states: <https://publicholidays.de/epiphany/>
