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

## The deliberate choice

I could have done the easy version. I have deep knowledge of the American Civil War, WWI, and several other eras. My own voice. Just hit record and go.

Instead I built the hardest possible version. Maximum distance from myself on every axis — age, nationality, academic register, era, even relationship to technology. A 72-year-old Bavarian academic who has never sent an email, talking about an era that does not exist in American consciousness, in a voice cloned from a real German historian, on a website his fictional grandson built.

The point was not the podcast. The point was whether a fully realized persona — age, nationality, academic register, emotional range, specific comedic voice — could be constructed and sustained entirely through AI tooling at maximum distance from the builder. Josef Ezekiel Von Gieslingen is the answer to that question.

The "I could have just talked" part matters. This wasn't hiding behind a persona because I couldn't do it myself. The persona was the hard problem. The era is Mars. The project was building the rocket.

---

## The persona

**Prof. Josef Ezekiel Von Gieslingen** — born Munich 1952, doctorate from LMU Munich, taught at Rutgers and Pennsylvania State University, has lived in America for over thirty years. His grandson Tyler built the website and handles all the technology. Josef just talks.

The character was built from scratch: full biography, recurring intellectual obsessions, emotional range across episodes, a specific comedic register. He deploys Gen-Z slang once per episode with maximum irony. He gets genuinely excited about Von Clausewitz. He has strong opinions about footnotes. He went on a walk after discovering podcasts and his wife called his grandson to ask if something had happened to him.

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

**Scripts:** Each episode runs 14–65 minutes of spoken content. Written to Josef's specific voice — academic precision, literary reference, and cross-era tangents, unedited. The diatribes are the soul of the show.

**Website:** Single HTML file. Interactive map of the German Confederation (1860) with CSS hotspot overlays — hover tooltips showing population, religion, and academic facts per state. Imperial eagle SVG. Parchment color scheme. Spotify embeds. Custom domain.

**Logo:** Circular seal design, German imperial tricolor, gold type. 1400×1400px for Spotify.

---

## What exists

- Episode 0 — *A Word Before We Begin* (~14 min) — who Josef is, why this podcast exists
- Episode I — *Arriving at Germany: 1860* (~65 min) — from Teutoburg Forest to the eve of unification
- Episode II — in production
- Full website with interactive map, imperial eagle, episode players
- Podcast live on Spotify
