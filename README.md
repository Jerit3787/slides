# Intro to PWN: Interactive Slides & Visual Memory Lab

Interactive, diagram-driven presentation slides for the **HTB Meetup IIUM 2025: Intro to PWN (ret2win)** workshop.

Hosted at: **[slides.danplace.tech](https://slides.danplace.tech)**

## Features

- **Interactive Visual Process Memory Map**: Clickable 64-bit memory segments (Stack, Heap, BSS, Data, Text) with live inspector detailing permissions, addresses, and exploitation role.
- **Visual Stack Frame Anatomy**: Diagram showing allocation vs buffer-fill growth directions and how bounds errors corrupt return addresses.
- **Live Interactive Buffer Overflow Simulator**: Real-time slider controlling byte inputs with visual memory cell corruption, CPU register HUD, and ret2win control flow hijacking.
- **Hands-On & Mini-CTF Deep Dives**: Aligned directly with the writeup at [ctf.danplace.tech](https://ctf.danplace.tech/posts/htb-meetup-iium/), including the 16-byte stack alignment trap (`movaps`) and `ret` gadget fix.
- **Zero Dependencies**: Pure HTML5/CSS3/JavaScript that runs offline or on any static hosting provider.

## Local Preview

Open `index.html` in your browser or run:

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Deployment

Automated via GitHub Actions on push to `main` with CNAME `slides.danplace.tech`.
