# Oaknest — Part Time Rental Listing Optimiser
## Handover Package

---

## What This Is

A personalised Airbnb listing optimisation tool built for Corne's Oaknest guesthouse in
Bloemfontein, Free State. The tool analyses the live listing against Airbnb's published
best practice guidelines and presents findings as an interactive mobile-first report —
designed in the style of an Instagram/LinkedIn carousel.

Built by: Nandus (brother) as a gift — framed externally as output from an automated
optimisation tool, not personal advice.

---

## The Listing

**Name:** Oaknest  
**URL:** https://www.airbnb.com/rooms/1651457771881931251  
**Location:** 27 Generaal Cronje Street, Bloemfontein (same street as Sentraal High School)  
**Host:** Corne — teacher, new host 2026  
**Type:** Entire guesthouse · 2 guests · 1 bed · 1 bath  

---

## Deliverables

### `deliverables/ptrlo-v4.html` — Main deliverable
The final interactive tool. Self-contained single HTML file. All images base64-embedded.
No external dependencies except Google Fonts.

**6 swipeable cards:**
- Card 0: Your listing as it stands (real photos, real data)
- Card 1: Score (61/100) + 3 quick wins + how the report works
- Card 2: Full score breakdown + what works / what to improve / what to add
- Card 3: Prioritised suggestions (Must Have / Quick Wins / Ideal State toggle)
- Card 4: Before and after discovery simulations per priority level
- Card 5: Copy-paste ready title, description, and host bio

**To deploy on Vercel:**
1. Rename `ptrlo-v4.html` to `index.html` (a copy already exists as `deliverables/index.html`)
2. Drag and drop into a new Vercel project
3. No build step required — it is a static single-file site

**To share directly:**
- Send the .html file — opens in any mobile or desktop browser
- Or share the Vercel URL once deployed

**To produce a PDF:**
- Open in Chrome on desktop
- File → Print → Save as PDF
- The print stylesheet hides navigation and toggles; all content expands

### `deliverables/index.html` — Vercel-ready copy
Same file as ptrlo-v4.html, renamed for direct Vercel drag-and-drop deployment.

### `deliverables/oaknest-listing-guide.pdf` — Reference PDF
A programmatic PDF export of all guide content. Note: this does not match the visual
design of the HTML tool and is included for reference only. The HTML print-to-PDF
method produces a better output.

---

## Key Copy (Ready to Use)

### Must Have Title
`Oaknest · private garden cottage · Bloemfontein`

### Quick Wins Description (~280 words)
Welcome to Oaknest — a private garden cottage named after the oak tree that shades our
property and keeps it cool even in a Free State summer.

The cottage is entirely yours. Private entrance, your own kitchen, your own bathroom, your
own quiet space. No shared areas, no other guests.

Whether you're in Bloemfontein for a school event — a parents' weekend, prize-giving, or
sports day — visiting the University of the Free State, or here for work, Oaknest offers
a calm and comfortable base in the heart of the city.

Inside: a fully equipped kitchen, strong WiFi, a dedicated work desk, and a bedroom
designed for proper rest.

Outside: a garden that earns its name. The oak tree provides natural shade. A private pool,
available year-round, and garden seating that feels like a second room.

Two covered carport bays included. Quiet residential neighbourhood. Easy access to all
major schools, the UFS campus, and the CBD.

Oaknest is a home, not a hotel. Come as you are.

### Host Bio
I'm a teacher in Bloemfontein with a love for quiet spaces and a well-kept garden.
Oaknest is my home — I've made it as comfortable for you as I have for myself.
I'm always available if you need anything during your stay.

---

## Three Must-Fix Actions (in order)

1. **Install smoke alarm + CO alarm** (~R400 at Builders Warehouse)
   Then tick both boxes under Safety & Property in the Airbnb listing.
   This removes a visible warning banner currently shown to all guests.

2. **Enable Instant Book** (10 minutes, free)
   Set guest requirements: verified ID + positive previous reviews.
   Without this, the listing is invisible to a large segment of filtered searches.

3. **Update the title** (2 minutes, free)
   Current: "A serene garden retreat. Rooted in comfort."
   New: "Oaknest · private garden cottage · Bloemfontein"

---

## Additional Platforms to List On

| Platform | Why | Cost |
|---|---|---|
| lekkeslaap.co.za | Afrikaans-first, school travel audience | Free |
| savenues.com | SA domestic + academic travellers | Free |
| School parent Facebook groups | Direct access to target guests | Free |
| WhatsApp booking link (wa.me) | SA guests prefer WhatsApp | Free |
| booking.com | Business/academic expense reimbursement | ~15% commission |

---

## Attachments Index

### listing-source/
- `oaknest-airbnb-listing.pdf` — Full PDF export of the live Airbnb listing
- `oaknest-airbnb-photos.pdf` — Photo tour PDF from the listing

### property-photos/
- `oaknest-pool-garden.jpeg` — Hero shot (pool and garden)
- `oaknest-exterior-patio.jpeg` — Exterior with white garden furniture
- `oaknest-bedroom.jpeg` — Bedroom interior
- `oaknest-oak-tree-illustration.png` — Illustrated oak tree used on splash screen

### design-references/
- `moodboard-carousel-ui.jpeg` — Pinterest moodboard (initial UI direction)
- `moodboard-listing-cards.jpeg` — Card-based listing UI reference
- `moodboard-app-style.jpeg` — App aesthetic reference
- `colorkit-palette.png` — Colour palette used (#789b8a sage, peach, cool greys)

### feedback-screenshots/
Progressive design feedback screenshots from the review rounds during build.

---

## Iterations (for reference only)

Build history — kept for context, not for use:

| File | Stage |
|---|---|
| oaknest-discovery.html | First search simulation concept |
| oaknest-full-guide.html | First full guide attempt |
| oaknest-guide-v3.html | Sourced guide with section structure |
| oaknest-guide-v4.html | Context-first narrative guide |
| ptrlo-app.html | First card-based app build |
| ptrlo-v2.html | Photo integration + before/after |
| ptrlo-v3.html | Full rebuild with all corrections |

---

## Sources Referenced Throughout

- Airbnb Resource Centre: airbnb.com/resources/hosting-homes
- Triad Vacation Rentals 2025: triadvacationrentals.com/blog/airbnb-algorithm-and-how-to-rank-higher
- Hostaway Algorithm Guide: hostaway.com/blog/airbnb-search-algorithm
- GuestReady Descriptions: guestready.com/blog/best-airbnb-descriptions-examples
- Uplisting Description Tips: uplisting.io/blog/airbnb-description-tips
- HostAI Title Research: gethostai.com/blog/best-airbnb-titles
- Rankbreeze Algorithm: rankbreeze.com/airbnb-algorithm
- Hostfully Ranking Guide: hostfully.com/blog/rank-higher-in-airbnb
- Complete Hospitality Management: completehospitalitymanagement.com/airbnb-description-mistakes

---

*Prepared June 2026. All recommendations based on Airbnb's published guidelines at time of production.*
