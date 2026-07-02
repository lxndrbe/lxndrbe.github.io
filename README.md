# LX Audiolabs — Bug Tracker

This is the public issue tracker for **LX Audiolabs CLAP plugins**.  
The actual website lives at **[lxndrbe.github.io](https://lxndrbe.github.io)**.

## 🐛 Report a Bug

1. **[Search existing issues](https://github.com/lxndrbe/lxndrbe.github.io/issues?q=is%3Aissue)** — open & closed — your bug might already be reported.
2. If not: **[Open a bug report](https://github.com/lxndrbe/lxndrbe.github.io/issues/new/choose)** — use the **Beta Bug Report** form for structured reports, or a blank issue for quick notes.

## 🔗 Links

| | |
|---|---|
| Website | [lxndrbe.github.io](https://lxndrbe.github.io) |
| Discord | [discord.gg/ew6kPtdDJ6](https://discord.gg/ew6kPtdDJ6) |
| YouTube | [@lxndrbe](https://www.youtube.com/@lxndrbe) |
| Sponsor | [github.com/sponsors/lxndrbe](https://github.com/sponsors/lxndrbe) |

## 🎛 Plugins

### Aether — Monitoring: Harman EQ + Crossfeed
Headphone correction for accurate mixing.  
**Place it:** Last in your **monitoring FX chain** (post-master, not printed).

### Equilibrium — Master Bus: Spectral Balancer
5-band crossover with per-band stereo width, pan, and goniometer.  
**Place it:** First on your **master bus** — balance before the mastering chain.

### Meridian — Group Bus: Shaper / Sculptor
5-band parametric EQ + soft-knee compressor + analog saturation.  
**Place it:** On **tracks or group channels** — sculpt any source.

## ⚠️ Known Issues

### Windows 10 — Animated Displays Are Blank
Audio processing and all static controls (knobs, sliders, buttons) work fine.  
**Animated displays** (spectrum analyzer, goniometer, peak meters) show as blank.  
This is a window-lifecycle mismatch between the Iced/wgpu GUI toolkit and Windows 10's compositor — not a GPU hardware problem. Windows 11 is the minimum supported platform for full visuals.

### macOS Intel — Not Supported
Plugins are compiled for **Apple Silicon** (ARM64). Intel Macs may not load them or may have degraded performance.

### DAW Support
CLAP format is supported in **Bitwig Studio, Reaper, Studio One, FL Studio**.  
Not supported: Ableton Live, Pro Tools, Logic Pro (without wrapper).

---

*Plugin source code is private. This repo hosts the website, beta downloads, and public bug tracking.*
