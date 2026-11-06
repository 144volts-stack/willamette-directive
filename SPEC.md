# Willamette Room Field Directive — Updated Spec for Imagine

## Goal
Polish the existing page into a higher-quality interactive experience. Keep the force-scroll, history trap, and story. Improve visuals, readability, and audio. Replace the coin drag with a Magic 8-Ball boot sequence.

## Live Page
https://144volts-stack.github.io/willamette-directive/

## Boot Screen — Magic 8-Ball
Replace the coin slot. Player must shake the 8-ball four times:
1. "Defective switch." — not the answer
2. "Try again."
3. "Turn off energy-saving settings in managed switch." — not the answer
4. "Replace Cat5 cable." — this is the entry point (what Travis wants Scott to do)

On the fourth shake, chiptune starts and the game begins. Each shake plays a short rattle sound.

## Visual Style
- Dark retro-arcade aesthetic
- 8-bit pixel elements mixed with modern readable typography
- Off-white or light amber text on solid dark panels
- 16–18 px minimum font size, high contrast for phones
- Green monospace only for terminal/boot sections
- 3D-ish depth on panels, subtle gradients, arcade cabinet framing
- Mobile-first, scales to desktop

## Story Arc
Travis Baumann installed a Yealink CM20 mic. It dies every morning at 3 AM. He blames a 30-foot 24-gauge CCA cable. Real cause is Comcast business gateway overnight DHCP maintenance. Scott (49-state AV installer, provisional patents, 14.4volts@gmail.com) gets talked down to. The page is Scott's revenge — every wrong answer Travis gives is a dead-end door.

## Paths (force-scroll, back button only at bottom)
1. **Ladder** — Mr. Hoot Common Core voltage drop lesson (number bonds, goldfish, sticker glue allergy, animated steps). Ends with "He chose poorly" (Indiana Jones Grail). Dial-up screech sting.
2. **Injector** — VCH port is not air-gapped. PoE injector suggestion. Dial tone.
3. **Switch** — Two-switch test. Tappable nightmare cards (VLAN no uplink, punched IP table, cursed RJ45, IP collision, Comcast overnight reboots, Yealink 169.254). Busy signal.
4. **Statics** — Permanent fix. Silence.
5. **Professional Courtesy** (final before dysentery) — Deposition with jokes. Ferrari line. Prove me wrong. 14.4volts@gmail.com.

## Audio (Web Audio API, no external files)
- Soft click on every page load
- Path-specific stings
- Cash register cha-ching on wrong clicks
- BSOD: "A process has died: TRAVIS.EXE"
- Windows 95 shutdown on deaths
- Magic 8-ball rattle on each shake
- Chiptune loop on boot (two square waves, triangle bass, 60 BPM)

## Technical Requirements
- History trap (pushState + popstate) so browser back button does nothing
- Fullscreen on first interaction
- Force-scroll before exit link appears
- Works on iPhone Safari, Android Chrome, and desktop
- All self-contained (no external JS/CSS except optional image URLs)

## Background Gags
- Drifting "Have you tried unplugging it?" text
- Rotating snake-oil speaker wire reel
- Occasional Grim Reaper fly-by

## Current File
The existing index.html in this repo is the starting point. Rebuild or heavily restyle it according to this spec.
