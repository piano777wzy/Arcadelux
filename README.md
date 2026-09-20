  Arcadelux body { max-width: 46rem; margin: 2rem auto; padding: 0 1.25rem; font: 1.05rem/1.6 -apple-system, Segoe UI, Roboto, sans-serif; color: #1a1a2e; background: #fafaff; } h1 { font-size: 2rem; color: #2d2b55; margin-bottom: 0.2rem; } h2 { font-size: 1.3rem; color: #4b3f8f; margin-top: 2rem; border-bottom: 2px solid #e6e3f5; padding-bottom: 0.3rem; } hr { border: none; border-top: 1px solid #ddd; margin: 2rem 0; } ul { padding-left: 1.4rem; } li { margin: 0.3rem 0; } strong { color: #2d2b55; } em { color: #6b5fa8; }

Arcadelux
=========

**A fully synthesised audio arcade. No recordings — every sound is generated the moment you hear it.**

Copyright © 2026 Riad Assoum. All rights reserved.

* * *

What it is
----------

Arcadelux is a self-contained arcade of 124 original games, played entirely by ear. It ships with no audio files of any kind. Every tone, voice, footstep, explosion, coin, engine, chicken and coconut you hear is generated in real time from raw waveforms as the game runs — a complete synthesiser, spatial audio engine and procedural music composer built from scratch. Nothing is sampled; nothing is streamed; the entire sound world is computed on the spot.

That single design decision shapes everything. Because the audio is synthesised rather than recorded, it can be placed with true binaural precision, pitched and bent continuously, and scored to match the tempo of play — and the whole game fits in a few megabytes with not one sound file inside it.

* * *

The arcade
----------

124 games across 8 themed worlds:

*   \*\*Rhythm Row\*\* — timing, pitch and memory.
*   \*\*Neon Alley\*\* — reflexes and stereo tracking.
*   \*\*Classic Corner\*\* — arcade legends rebuilt for the ear: Snake, Pong, Breakout, Invaders, Asteroids and more.
*   \*\*Deep Space\*\* — flight, physics, docking and hunting in three dimensions.
*   \*\*Puzzle Parlour\*\* — pure thinking; nothing moves until you do.
*   \*\*Carnival Row\*\* — sideshow booths: coconut shies, ring tosses, hammer strikes, fortune wheels.
*   \*\*The Night Shift\*\* — jobs, not games: keep a whole system running through the small hours.
*   \*\*Sound Lab\*\* — ear training that sharpens the sense every other game depends on.

Every cabinet is playable start to finish with keyboard or game controller, and every cabinet has a **Hardcore mode** hand-tuned as a genuinely different, harder challenge — not merely a faster version of the same game.

* * *

Features
--------

**A true synthesiser.** Multiple sound engines — chip, analog, FM, acoustic and hybrid — each with its own character, selectable and unlockable. Sounds are built from oscillators, envelopes, filters and noise, shaped per game.

**Binaural 3D audio.** A full spatial engine places sound in real space around your head — left and right, near and far, and genuinely above, ahead and behind — using interaural timing and level differences and head-related filtering. Many games move into full 3D in Hardcore mode.

**Procedural music.** An original composer writes the backing music live, in a proper song form, matched to each game's mood and tempo, in a set of unlockable styles. No two sittings sound quite the same.

**A progression that rewards playing.** Earn coins by playing well and spend them at the shop; earn experience by playing at all and climb a player level that no bad run can dent. New cabinets, engines, sound banks, music and modes open as you rise — coins and levels gate the arcade together, so neither buys the endgame alone. A daily challenge, gem-driven Rewards Hall, hot-streak multipliers and 326 achievements keep the long game alive.

**Built for screen readers.** Everything is spoken. Arcadelux speaks through NVDA, JAWS and other readers via Tolk, through NVDA's controller client directly, or through SAPI 5 — chosen automatically. A speech-speed calibration tool teaches the game exactly how fast your reader talks, so messages are never cut off or left hanging.

**Fully localised.** Every word the game speaks — menus, help, results, sound cues, achievements — is translatable, with a strict build-time guarantee that nothing untranslatable can ship. Arabic is included in full.

**Controller support.** Any connected gamepad works everywhere: d-pad, analog stick and face buttons map straight onto the game, and controllers can be plugged in mid-session.

* * *

Credits
-------

**Design, code, music and sound design:** Riad Assoum.

**Development assistance:** portions of the engineering — game balancing, localisation tooling, test harnesses and refactoring — were carried out with the assistance of Claude, an AI assistant by Anthropic, working under the author's direction.

**Technologies and resources:**

*   \*\*Python\*\*, with \*\*NumPy\*\* for real-time waveform synthesis and \*\*pygame\*\* for audio playback and input.
*   The binaural elevation cues are informed by the \*\*MIT KEMAR\*\* head-related transfer function measurements (Gardner & Martin, 1994).
*   Screen-reader speech via \*\*Tolk\*\* (Davy Kager), NVDA's \*\*controller client\*\*, and Microsoft \*\*SAPI 5\*\*.
*   Several classic games are audio reimaginings of public-domain arcade concepts; all code, music and sound are original to this project.

* * *

Accessibility statement
-----------------------

Arcadelux was built from the ground up to be played without sight. It is not a visual game with audio bolted on: the audio _is_ the game. Menus, help, game state and results are all spoken; navigation is consistent across every cabinet; and the interface adapts to your screen reader's speed. If something is unclear by ear, that is considered a bug.

* * *

_Arcadelux — every sound made from nothing, the moment you hear it._
