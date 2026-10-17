# MizoDSP — Official Website

Official website for **MizoDSP** — Mizoram's First Audio Software Company — featuring **ABVox**, the definitive signature vocal chain plugin engineered by Andrew Bawitlung.

Live site: [https://mizodsp.github.io](https://mizodsp.github.io)

No build step, no frameworks, zero trackers, pure HTML5 and modern CSS.

```
website/
├── index.html                  Home — MizoDSP brand, featured ABVox, promo video, story, series
├── abvox.html                  ABVox product page — 6-module DSP architecture, video, b-roll, specs
├── styles.css                  Shared stylesheet with dark accents & responsive design
├── favicon.svg                 Vector favicon
└── assets/
    ├── MizoDSP logo.png        Official MizoDSP company logo (1505 × 660)
    ├── AB_VOX.png              ABVox plugin logo (1778 × 368)
    ├── ABVox_Plugin_Render.png Rendered plugin interface (1024 × 341)
    ├── BRoll1.png              Studio photo: Andrew Bawitlung at the console
    └── BRoll2.jpg              Studio photo: ABVox tracking session
```

## Viewing the Site

Open `index.html` directly in any web browser, or launch a local test server:

```powershell
cd website
python -m http.server 8137
# then open http://127.0.0.1:8137/ in your browser
```

## ABVox Signal Chain & DSP Architecture

1. **Tone**: Class-A 1073 warmth and console saturation with 218 Hz low-mid warmth, presence bite at 7.9 kHz, and 16 kHz air shelf.
2. **Dynamics**: 1176 & LA-2A chain type dual-stage compressor (fast FET transient grab into smooth optical leveling).
3. **De-Esser**: Algorithmic style dual-path dynamic frequency splitting with 32-sample sliding-window RMS detection and dynamic resonance notch filter.
4. **Delay**: Ping-pong analog tape echo with S1 stereo imaging, 0.1 Hz tape wow & flutter modulation, Abbey Road bandpass send filters (188 Hz – 3.5 kHz), and warm saturated tape feedback.
5. **Doubler**: Reel ADT type doubler featuring Abbey Road-inspired artificial double tracking with stereo micro-pitch detuning.
6. **Reverb**: Chamber reverb plates style with calibrated 55.6 ms pre-delay, diffuse all-pass comb filtering, and Abbey Road post-EQ shaping.

## Video Showcase

- Embedded official YouTube promo and sound demo: `https://youtu.be/3EMnWuiMG0U`
