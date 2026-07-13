# Match Day

A companion app for calm screen-time transitions: it turns the end of watching time into the familiar, predictable end of a soccer match.

## How to run it tonight

`index.html` is the whole app — no build, no dependencies, works offline once loaded.

1. Get the file onto the phone/tablet, any of these works:
   - AirDrop `index.html` to the device and open it in Safari, **or**
   - on this Mac run `cd match-day && python3 -m http.server 4980`, then on the phone (same Wi-Fi) open `http://<this-mac's-ip>:4980`.
2. Prop the device up next to the TV, tap **New match**, pick the length, tap **Kickoff**.
3. Parent settings (language, volume, warning times, 2-minute test match, reset points): press and **hold the ⚙ button for 3 seconds**.

Tip: run the 2-minute test match from settings once to see the whole ritual before using it for real.

## What's next (native iOS, Phase 2)

- SwiftUI app with the same state machine and ritual, so it can run full-screen in Guided Access with real background audio.
- Recorded stadium/whistle audio to replace the synthesized sounds.
- Optional: coach character animation and per-day match schedule.
