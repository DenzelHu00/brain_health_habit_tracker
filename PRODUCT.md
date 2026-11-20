# Product

## Register

product

## Users
Middle-aged adults, roughly 40 to 65, who want to look after their memory and brain health as they age. Many are not tech-focused. They open the tracker once or twice a day, often on a phone, sometimes on a laptop, to check off a habit they just did (a walk, a phone call with a friend, a good night's sleep). Sessions are short: open, tap, feel good, close. Some will have mild presbyopia or reduced fine motor precision.

## Product Purpose
A single-page browser habit tracker built as a prototype for a university neuroscience group project (NSCI 140) on aging and memory. It helps people adopt at least one evidence-based habit linked to brain health, drawn from modifiable dementia risk factors discussed in the 2024 Lancet Commission report. Success is a user who picks one to three habits, keeps checking them off for weeks, and never feels judged for a missed day. It is educational, not medical, and never claims to prevent dementia.

## Brand Personality
Calm, warm, encouraging. The voice is a supportive friend, not a coach or a clinician. Plain, short sentences. Celebrate progress quietly; treat missed days as normal ("Missed a day? That's normal. Pick it back up today."). Emotional goal: the user closes the app feeling capable and a little proud.

## Anti-references
- Clinical or medical apps: hospital blues, sterile white, symptom-checker or patient-portal styling.
- Gamified streak pressure: flames, guilt nudges, leaderboards, mascots, loss-aversion copy (Duolingo-style).
- Tech dashboards: dense charts, dark neon, data-heavy panels, KPI tiles.

## Design Principles
1. **One obvious action.** On any day, the next thing to do (check off a habit) is the most visible thing on screen.
2. **Kindness over metrics.** Numbers inform, they never scold. Progress is framed as what you did, not what you missed.
3. **Readable first.** Size, contrast and spacing are set for 40 to 65 year old eyes and thumbs before any aesthetic choice.
4. **Small is the strategy.** The interface itself models "start small": few elements, few choices, no clutter.
5. **Honest science.** Plain-language explanations, careful claims ("supports brain health"), visible disclaimer.

## Accessibility & Inclusion
- WCAG 2.2 AA minimum: 4.5:1 body text, 3:1 large text and UI boundaries, visible focus states.
- Base font size at least 18px; tap targets at least 44px.
- Never rely on colour alone (done days show a check mark, not just a fill).
- Respect prefers-reduced-motion and prefers-color-scheme.
- Works fully with keyboard and screen readers; data stays local (localStorage) with graceful fallback.
