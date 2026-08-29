# Aperture // Orbit

A lightweight, zero-dependency Progressive Web App (PWA) designed for night-sky shooters, astrophotographers, and casual stargazers. Built with adaptive mobile-first ergonomics, live GPS atmospheric telemetry, physics-based ambient canvas particles, and native calendar ingestion.

---

## What's Inside

* **Adaptive Dual-Pane & Ergonomic HUD:** Automatically shifts to a persistent left-rail navigation dock with a side-by-side list and Sky Deck view in landscape orientation.
* **Auto-Collapsing Month Drawers:** Clean hierarchical event layout organized by year and month. Drawers automatically collapse unless they match the active observing month.
* **Ambient FX Particles:** Theme-reactive background canvas with falling cherry blossom petals, floating jade prisms, shimmering liquid gold glints, and ocean pearl beads.
* **6 Preset Color Palettes:** Cherry Blossom, Mellow Jade, Liquid Gold, Ocean Pearl, Pitch Black (OLED), and Snow White with light/dark theme flipping.
* **4 UI Density Modes:** Focus (starred targets only), Slim (compact top upcoming), Standard, and Detail Heaven.
* **Astro Red-Light Night Vision:** Full-app monochrome red HUD mode (`#ff2200`) designed to preserve dark-adapted scotopic vision in the field.
* **Observer Sky Deck & Exposure Math:** Real-time lunar illumination, geomagnetic Kp index, live Open-Meteo atmospheric telemetry, and pinpoint shutter threshold calculator (500 Rule / NPF).
* **Calendar Sync & Feed Ingestion:**
  * One-tap direct clipboard paste for calendar feed URLs.
  * Native WebCal / `.ics` URL sync via proxy parsing.
  * Local `.ics` file upload and parsing.
  * Recommended space calendar integration preset ([lkorth.github.io/space-calendar](https://lkorth.github.io/space-calendar/)).
  * Long-press event cards (0.6s) to directly export configured `.ics` alarms.
  * One-tap custom feed purge to reset back to regional baseline calendars (North America, Europe, Southern Hemisphere).

---

## Install as a Mobile App (PWA)

* **iOS (Safari):** Open the website in Safari → Tap **Share** → Tap **Add to Home Screen**.
* **Android (Chrome):** Open the website in Chrome → Tap the **three dots menu** → Tap **Install App** or **Add to Home Screen**.

---

## Third-Party Libraries & APIs

* **Icons:** [Lucide Icons](https://lucide.dev)
* **Weather & Cloud Cover Telemetry:** [Open-Meteo API](https://open-meteo.com)
* **Recommended Space Feeds:** [Space Calendar by lkorth](https://lkorth.github.io/space-calendar/)

---

## Credits & Acknowledgments

* **Developer:** **[@27ozig](https://instagram.com/27ozig)**
* **Aubree:** For testing location services and inspiring the *Cherry Blossom* theme.
* **Thomas:** For introducing the wonder and scale of celestial observation.
* **Community:** Thank you to everyone supporting the project on Instagram.
 * Slim: Compact card footprint displaying the closest upcoming events.
 * Standard: Balanced layout for general event tracking.
 * Detail Heaven: Wide-open data density with inline optical setups (Shutter, ISO, Aperture, Peak Window) and field notes. In Landscape Mode, it automatically splits into a dual-pane workstation with a scrollable event feed on the left and a sticky Sky Deck HUD on the right.
3. Themes & Physics-Based Particle Shaders
Six built-in themes featuring light/dark variants, smooth animated toggles, and dynamic canvas particle systems:
 * Cherry Blossom: Soft rose crystal glass with 3D fluttering, tumbling blossom petals.
 * Mellow Jade: Frosted emerald glass with floating bioluminescent radiant spores.
 * Liquid Gold: Metallic sheen with shimmering bokeh ember dust.
 * Ocean Pearl: Pearlescent fluid gradient with rising buoyant bubbles.
 * Pitch Black: Pure AMOLED zero-particle black with high-contrast starlight accents.
 * Snow White: Clean alabaster card deck with zero background distractions.
 * Astro Night Vision: Instant red-monochrome mode (#ff2200) designed to preserve dark-adapted eyesight in the field.
4. Geo-Aware Regional Calendars & GPS
 * Automatic Geolocation: Calibrates weather data and filters regional events based on your coordinates.
 * Pre-Cached Astronomy Packs: Built-in offline event streams for North America, Europe, and the Southern Hemisphere.
 * Custom Calendar Sync: Ingest .ics files directly or paste live webcal:// URLs without backend servers.
 * Long-Press Calendar Alerts: Press and hold (600ms) any starred event card to export an .ics reminder directly to your native device calendar (Google Calendar / Apple Calendar).
5. Field Tools & Exposure Calculators
 * Pinpoint Shutter Calculator: Instant NPF and 500 Rule calculation to prevent star trailing based on focal length and sensor crop factor (Full Frame, APS-C, Micro Four Thirds).
 * One-Tap Route Navigation: Launches turn-by-turn coordinates directly into Google Maps or Apple Maps.
Field Handbook & Companion Setup
Recommended Sky Alignment Tools
For live celestial alignment and constellation identification, pair Aperture // Orbit with:
 * Android: Sky Map (lightweight, open-source real-time celestial viewer).
 * iOS Alternative: Stellarium Mobile or Night Sky for real-time azimuth and zenith tracking.
Dedicated Camera Setup (DSLR / Mirrorless)
 * Manual Focus Pinpoint: Set your lens to MF. Turn on Live View on your rear LCD, zoom digitally to 10x on a bright anchor star (e.g., Vega, Jupiter), and adjust the focus ring until the star is as small and sharp as possible.
 * Aperture: Shoot at wide apertures (f/1.4 to f/2.8). If your lens shows coma aberration in the corners, step down 1/3 of a stop.
 * Noise Reduction: Disable in-camera Long Exposure Noise Reduction so you can capture consecutive frames without delay for external stacking.
Installation (PWA)
Host these files on GitHub Pages or any static web host:
 * iOS (Safari): Open the website link -> Tap Share (square with up arrow) -> Tap Add to Home Screen.
 * Android (Chrome): Open the website link -> Tap the three dots menu -> Tap Install app or Add to Home screen.
License & Attribution
Copyright (c) 2026 @27ozig.
Free for personal and non-commercial astrophotography use. Ensure explicit creator credit (@27ozig) is preserved in distributed copies.
