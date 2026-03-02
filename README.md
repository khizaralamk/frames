# McLaren 720S — Scroll Experience

A premium scroll-driven frame-by-frame animation website for the McLaren 720S, built for the **#FigmaMakethon**. This project is for **educational purposes only** and is not affiliated with or endorsed by McLaren Automotive.

## How It Was Made

- **Design:** Created using [Figma Make](https://figma.com)
- **Code:** Generated with [Claude Opus 4.6](https://claude.ai) (Anthropic)
- **Video:** Generated using [Google Gemini Nano Banana 2](https://deepmind.google) with **Veo 3** for video generation
- **Frames:** Video output was broken into 81 sequential PNG frames for the scroll animation

## Tech Stack

- **HTML5 Canvas** — Full-screen frame rendering with cover-fit algorithm
- **GSAP 3.12** — ScrollTrigger for scroll-linked frame scrubbing and reveal animations
- **Lenis 1.1** — Buttery smooth scroll synchronized with GSAP ticker
- **Vanilla JavaScript** — No frameworks, no build tools
- **Google Fonts** — Saira (headings) + Lexend (body)

## Features

- Cinematic entry screen with audio unlock
- Reverse frame intro (frame 36 to 1) played at 22fps on enter
- Scroll-driven frame animation (81 frames)
- Counter animations for key stats (0-60 mph, power, weight)
- Specifications grid and detailed about section
- Fully responsive layout
- GSAP-powered scroll reveal animations throughout

## Disclaimer

This project was created solely for educational and hackathon purposes as part of **#FigmaMakethon**. All McLaren branding, logos, and product information are the property of McLaren Automotive Ltd. This is not an official McLaren product.

## License

For educational use only. Not for commercial distribution.
