# Echo Mo — Generative Ambient Music Studio

Every note composed by code, in real time. An elegant generative ambient music studio: pick a mood, press play, and listen to an endless pentatonic composition no one has ever heard before — and never will again.

🎧 **Live demo:** https://artzdesignmo.github.io/echo-mo/

## Features

- **Generative composition engine** — a random-walk melody generator over pentatonic scales, with natural phrasing, rests, and drift; soft pad chords and sparse bells underneath
- **4 moods** — Dawn (warm major pentatonic), Dusk (amber minor), Night (deep indigo), Zen (sparse high stillness), each with its own scale, palette, and pacing
- **Music-box timbre** — sine + octave shimmer through a generated convolution reverb, all synthesized live with WebAudio (no samples, no files)
- **Living visuals** — every note blooms into a soft orb that drifts upward; a pitch hairline traces recent notes
- **Controls** — tempo (40–120 bpm), density (sparse → rich), volume
- **OpenX standards** — Dela Gothic One headline, EN/中文 toggle (default EN), white / silver / black theme saved to localStorage

## Tech

Vanilla HTML/CSS/JS + WebAudio API + Canvas 2D. No dependencies, no build step, no backend. The reverb impulse is generated in code.

## Run locally

Open `index.html` in a browser (audio requires a user gesture — press play).

---

☕ [Buy Me a Coffee](https://buymeacoffee.com/whynotartmoney)

Part of the [OpenX](https://openx-mo.vercel.app/) open-source series.
