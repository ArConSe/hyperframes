# ArConSe — Company Introduction

## Style Prompt
Dark, cinematic, and professional. A construction and sustainability brand from the Philippines. Warm earth tones meet deep navy. Typography-led — the brand name commands authority. Subtle green accents signal environmental responsibility. Depth comes from radial glows and measured motion — no gradients, no gimmicks.

## Colors
- `#0D1B2A` — Background. Deep navy. Authority and depth.
- `#F0EAD2` — Primary text. Warm off-white. Earth-toned, readable.
- `#6A994E` — Accent green. Sustainability, growth, nature.
- `#DDA15E` — Secondary accent. Warm amber. Construction, earth.
- `rgba(106,153,78,0.04–0.20)` — Glow layer. Low-opacity green for depth without linear gradients.

## Typography
- **Poppins** (800, 700, 600, 300) — Primary. Headlines, brand name, taglines.
- **Roboto** (300) — Secondary. Subtitles, metadata, supporting copy.

## Motion
- Entrances: slide + fade. `power3.out` for hero elements, `power2.out` for supporting, `expo.out` for accents.
- Transitions: medium blur crossfade (0.55s, 12px blur peak).
- No exit animations except final scene fade to black at 9.5s.

## What NOT to Do
- No gradient text (`background-clip: text`)
- No cyan, purple, or neon accents — stay in the green/amber/navy family
- No linear gradients — radial only (avoids H.264 banding)
- No jump cuts — every scene change uses a blur crossfade
- No identical weights across elements — vary 300/700/800 for visual rhythm
