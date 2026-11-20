# Royal Bengali Interactive Wedding Invitation

### 💍 Puja Deb & Dipayan Bhowal

An interactive, self-contained HTML wedding invitation crafted for **Puja Deb & Dipayan Bhowal**, designed to be sent directly to guests over WhatsApp as a document/file (`Wedding_Invitation.html` or `index.html`). It runs completely offline in any modern mobile or desktop browser without requiring website hosting, node servers, or external javascript frameworks.

---

## 🎨 Visual Aesthetic & Concept
- **Background Scenery**: Royal Bengali lakeside wedding mandap pavilion framed with carved marble arches, hanging brass bells, lanterns, draped sheer fabrics, marigold & rose garlands, and the iconic Kolkata Victoria Memorial dome across the water under an auspicious golden-red "শুভ বিবাহ" sky.
- **Palette**: Royal Bengali Wedding theme featuring Auspicious Ceremonial Red (`#580816`, `#800E22`, `#AD1530`), Radiant Golden-Yellow / Haldi Amber (`#FFD700`, `#FFB800`, `#FFE58F`), Antique Gold (`#D4AF37`, `#F7E6B5`), and Ivory Parchment (`#FDFBF7`, `#F8F3E8`).
- **Typography**: Royal serif titles (`Cinzel` / `Playfair Display`), elegant calligraphy (`Great Vibes`), warm serif body (`Cormorant Garamond` / `Georgia`).
- **Traditional Motifs**: Bengali auspicious invocations (`॥ শ্রী শ্রী প্রজাপতয়ে নমঃ ॥`, `॥ শুভ বিবাহ ॥`), intricate Paisley / Kalka floral vector elements, and gold filigree corners.
- **Unveiling Flow**:
  1. Grand lakeside wedding mandap scene with organic sinusoidal floating golden fireflies, clear panoramic views of the water, Victoria Memorial dome, and auspicious red-gold "শুভ বিবাহ" in the sky.
  2. Floating regal gold **Royal Shehnai** music controller at the top right with an animated 4-bar sound equalizer.
  3. Elegant, glowing **OPEN INVITATION** gold button at the bottom of the screen with a gentle breathing pulse.
  4. Tapping **OPEN INVITATION** initiates a **Gentle Cinematic Fade & Particle Drift**:
     - The background scenery gains a dreamy **cinematic depth-of-field soft blur** and warm golden backlight aura.
     - A radiant **Golden Sparkle Wash** (cascading golden stars, glowing embers, and champagne dust) showers downwards across the screen.
     - The **Royal Golden Scroll (রাজকীয় ফরম্মান)** smoothly unrolls downwards with soft optical blur-to-sharp crossfade, accompanied by swaying golden silk tassels.
     - Auspicious **Royal Shehnai Instrumental Melody** (Raga Kedar Dhun by Ustad Bismillah Khan) automatically fades in smoothly, setting an enchanting celebratory ambiance.
  5. At the top of the unrolled parchment is an ornate, sacred circular medallion of **Lord Ganesha (শ্রী গণেশ)** with `॥ ॐ শ্রী গণেশায় নমঃ ॥` and `॥ শুভ বিবাহ ॥`.
  6. Interactive buttons on the scroll allow guests to RSVP instantly on WhatsApp (`9874839969`), view the Google Maps venue location in a new tab, and save the wedding date directly to their calendar (.ics).
  7. Smooth **Roll Up** navigation gently restores background focus and brings back the opening invitation button, while music continues or can be paused at will.

---

## 📁 Repository Structure
```text
Wedding_card/
├── index.html                             # The standalone interactive wedding invitation (self-contained)
├── Wedding_Invitation.html                # Direct shareable copy for WhatsApp document sending (self-contained)
├── README.md                              # Project documentation & wedding config
├── wedding_invitation_setup_instructions.md # Project design and requirements specification
├── Audio/
│   ├── shehnai_wedding.mp3                # Auspicious Royal Shehnai loop (Raga Kedar Dhun)
│   ├── shehnai_dhun.mp3                   # Extended classical Shehnai recording
│   ├── traditional_bengali.aac            # Bengali folk wedding melody
│   └── shubho_bibaho.aac                  # Shubho Bibaho instrumental track
└── Images/
    ├── ganesh_emblem.jpg                  # Original high-res sacred Lord Ganesha artwork
    ├── ganesh_emblem_opt.jpg              # Optimized Ganesha scroll header emblem
    ├── ganesh_emblem.webp                 # Ganesha WebP asset
    ├── wedding_mandap_bg_wide.jpg         # Full 16:9 widescreen panoramic landscape mandap scenery asset
    ├── wedding_mandap_bg.webp             # Optimized widescreen WebP image
    ├── wedding_mandap_bg.jpg              # Original portrait mandap scenery asset
    └── Venue_image.png                    # Venue photo reference
```

---

## 📅 Event & RSVP Details

| Field | Configured Detail |
|---|---|
| **Bride** | Puja Deb |
| **Groom** | Dipayan Bhowal |
| **Monogram** | `P & D` |
| **Wedding Date** | Monday, 18th January 2027 |
| **Time** | 7:00 PM Onwards |
| **Venue** | Lalita Banquet & Guest House |
| **Address** | 97, Keshab Chandra Sen Street, near City College, College Street Area, Kolkata - 700009 |
| **Google Maps Pin** | [Open in Google Maps](https://maps.google.com/?q=Lalita+Banquet+%26+Guest+House+97+Keshab+Chandra+Sen+Street+Kolkata+700009) |
| **WhatsApp RSVP** | `+91 9874839969` |
| **Save The Date** | Generates & downloads `Puja_and_Dipayan_Wedding.ics` calendar file |
| **Back Button** | Integrated top and bottom "Back to Envelope" navigation inside the card |

---

## 📱 How to Test & Share

1. **Local Preview**: Double-click or open `Wedding_Invitation.html` (or `index.html`) in any web browser (Chrome, Safari, Edge, Firefox).
2. **WhatsApp Sharing**:
   - Send `Wedding_Invitation.html` directly to guests as a **Document** attachment on WhatsApp.
   - Guests tap the received document and open it in their phone browser (Chrome on Android, Safari on iPhone).
