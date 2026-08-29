Aperture // Orbit
A client-side Progressive Web App (PWA) built for astrophotographers, eclipse chasers, and night-sky observers. Zero dependencies, zero scrapers, client-side .ics calendar ingestion, real-time exposure calculations, and responsive HUD design for both mobile and landscape field rigs.
Key Features
1. Three-Tab Control Hub
 * List: Searchable, category-filtered celestial target feed with multi-year and monthly drawers. Includes instant filtering by visibility criteria (Naked Eye, Tripod Required, Lunar, Solar, Meteors, Aurora, Milky Way, Planets).
 * Sky Deck: Real-time lunar phase/illumination tracker, live Kp index telemetry, and local atmospheric cloud cover and temperature via Open-Meteo.
 * You: Central configuration panel for UI density presets, theme engines, pre-cached regional calendar packs, and backup/restore controls.
2. UI Density & Display Modes
 * Focus: Strips interface noise down to Starred targets only, displaying complete inline optical specifications and locking navigation to List and You.
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
