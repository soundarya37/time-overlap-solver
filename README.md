The Nine-Hour Overlap

A quick, honest answer to "is it too late to call?" — built for the real gap between adult children and parents living time zones apart, not for people who already do the math easily.

Two clocks side by side don't solve this. Knowing the number doesn't tell you if it's a good moment — only knowing someone's actual routine does. This tool turns real, live time-zone data plus each person's own wake/busy/sleep routine into a plain verdict: call now, wait, or keep it short.

Features
Live times pulled from real IANA time zones (America/Mexico_City, Asia/Kolkata), not a hardcoded offset — accurate through DST and any future zone changes
A single plain-language verdict at the top: "Good time to call," "Probably asleep — try after 7:00 AM their time," etc. — no time-zone math required to read it
Two animated sky cards per city — real dawn/day/sunset/night gradients, a sun or moon on a live arc, drifting clouds, twinkling stars at night — with the critical info (time, status) shown separately in high-contrast plain text below the animation
A 24-hour "day, side by side" timeline showing both routines and the actual overlapping free windows
Editable routines (wake, busy start/end, sleep) for each person, saved privately per device
One-tap "copy a message" for each direction, generated from real overlap-window calculation — not a guessed anchor point — so it can be sent once and pinned, ending the need to ask "is now okay?" every time
Installation

No installation needed. It's a single HTML file with no build step and no dependencies beyond two Google Fonts loaded via CDN.

Download nine-hour-overlap.html
Open it in any modern browser, or host it on any static host (Netlify, Vercel, GitHub Pages)
Usage

Open the file — the verdict banner updates live, refreshing every 30 seconds. Open "Adjust routines" to set each person's actual wake time, busy window, and sleep time; the verdict and timeline recalculate immediately. Use the two "Copy a message" buttons to generate a ready-to-send text describing the real good-call windows, converted into the recipient's own local time.

How the overlap is calculated

Each profile's day is divided into free / busy / asleep based on its own routine. To find good call windows, the tool steps through the recipient's 24-hour day in 15-minute increments, converts each point into the sender's local time using the real live time-zone offset, and keeps only the stretches where both people are free. Because the offset between two zones isn't always a clean number of hours, this can surface more than one good window a day — which a simple two-anchor guess would miss.

Data & privacy

Routines are saved locally to this device only (not shared with anyone else who might open the file). No account, no server, no analytics.

Roadmap
Support for adding a third city/person
Weekly variation, if routines genuinely differ by weekday
A stripped-down, verdict-only view for a lower-friction glance
Author

Built by Soundarya as part of an ongoing series of single-file, botanical-dark creative tools — alongside Kolam Weaver, Rasam vs. Salsa, The Book Vault, the Vibe Coding Starter Kit, and Guadalajara, By Newcomer.

License

MIT
