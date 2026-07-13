# Match Day

A companion app for calm screen-time transitions: it turns the end of watching time into the familiar, predictable end of a soccer match.

## How to run it tonight

Easiest: open **https://zevpad.github.io/match-day/** on the phone or tablet. Once loaded it keeps working offline (everything, including the final-stretch song, is inside the one page).

No internet? `index.html` is the whole app — AirDrop it to the device and open it in Safari, or serve it from a computer on the same Wi-Fi (`python3 -m http.server` in this folder).

1. Prop the device up next to the TV, tap **New match**, pick the length, tap **Kickoff**.
2. Parent settings (language, volume, warning times, match-controls PIN, reset points): press and **hold the ⚙ button for 3 seconds**. Run the **2-minute test match** from the top of settings once before the first real match.
3. During a match, the small ⚙ in the corner (PIN) offers pause ("injury stoppage") and end-match-now.

## What's next (native iOS, Phase 2)

- SwiftUI app with the same state machine and ritual, so it can run full-screen in Guided Access with reliable background audio.
- Recorded referee whistle to replace the synthesized one.
- Optional: coach character animation and per-day match schedule.
