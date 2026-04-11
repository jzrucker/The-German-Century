# The German Century: 1860–1913

**Live site:** [thegermancentury1871podcast.com](https://thegermancentury1871podcast.com)

An AI-generated history podcast about Imperial Germany. Serious, long-form, narrative history — told by a fictional retired German professor and his grandson.

---

## Why this exists

Three reasons, in order of honesty:

1. I wanted to build a persistent AI persona — a real character with a biography, a voice, a specific worldview, and long-form content people actually want to spend time with. Not a chatbot. Not a demo. Something that feels like it exists independently.

2. I wanted to demonstrate the full AI production stack — script generation, voice synthesis, persona design, web deployment — as a single cohesive project rather than isolated tools.

3. I listen to somewhere between 1,000 and 2,000 hours of history podcasts a year. This era is almost entirely absent from English-language audio. I needed something to listen to at the gym.

This is also a specific thesis about the era: 1870s Germany was Silicon Valley before Silicon Valley. Siemens. BASF. Bayer. The research university as a concept. The PhD. The internal combustion engine. X-rays. Aspirin. All of it, in one country, in one generation. That story has never been told in English audio. That is the gap this fills.

---

## The persona

**Prof. Josef Ezekiel Von Gieslingen** — born Munich 1952, doctorate from LMU Munich, taught at Rutgers and Pennsylvania State University, has lived in America for over thirty years. His grandson Tyler built the website and handles all the technology. Josef just talks.

The character was built from scratch: full biography, recurring intellectual obsessions, emotional range across episodes, a specific comedic register. He deploys Gen-Z slang once per episode with maximum irony. He gets genuinely excited about Von Clausewitz. He has strong opinions about footnotes.

The design question was whether a fictional persona could carry serious long-form academic content convincingly — and whether the character itself could become the product, not just a delivery mechanism.

---

## How it was built

| Layer | Tool |
|-------|------|
| Scripts | Claude (research, writing, character voice, episode structure) |
| Voice | ElevenLabs (custom voice, Creator plan) |
| Audio editing | MP3Cut, Audacity |
| Image generation | ChatGPT |
| Website | Vanilla HTML/CSS/JS — no frameworks |
| Hosting | GitHub Pages + custom domain (Namecheap) |
| Distribution | Spotify for Podcasters |

**Voice:** Custom voice built and refined in ElevenLabs Voice Lab. Pacing controlled through break tags and sentence structure rather than emotion tags — the v2 model responds more reliably to punctuation and rhythm than to explicit emotional direction.

**Scripts:** Each episode runs 14–65 minutes of spoken content. Written to Josef's specific voice — academic precision, literary reference, street vernacular, and philosophical tangent, simultaneously and unedited. Cross-era diatribes are the soul of the show.

**Website:** Single HTML file. Interactive map of the German Confederation (1860) with CSS hotspot overlays — hover tooltips showing population, religion, and academic facts per state. Imperial eagle SVG. Parchment color scheme. Looks exactly like something a retired professor's grandson built.

**Logo:** SVG, 3000×3000px. German imperial tricolor with the show name superimposed in gold. Built for Spotify and podcast directories.

---

## What exists

- Episode 0 — *A Word Before We Begin* (~14 min) — who Josef is, why this podcast exists
- Episode I — *Arriving at Germany: 1860* (~65 min) — from Teutoburg Forest to the eve of unification
- Episode II — *A Tour of the German World, 1860* — in production
