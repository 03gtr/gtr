# GTR Automotive Business Card Prototype

Mobile-first cinematic automotive digital business card.

- Supplied GTR image used as the hero visual.
- Loading sequence -> ignition -> UI reveal.
- Cinematic camera push, scan line, red light flare and subtle cabin shake.
- Social buttons are ready for real Instagram / Snapchat / WhatsApp URLs.
- Audio hook: place the licensed/owned real GTR engine recording at `assets/gtr-roar.mp3`.

Important browser behavior: mobile browsers generally block autoplay with sound until a user gesture. The prototype therefore attempts playback after loading and exposes `START ENGINE` as a fallback when autoplay is blocked.
