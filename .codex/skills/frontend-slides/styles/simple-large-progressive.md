# Simple Large Progressive

## Use When

Use this project style when a talk should feel simple, readable, and speaker-led.

It is especially useful for Korean internal talks where the presenter wants large type, calm pacing, and step-by-step disclosure instead of dense slides.

## Layout Rules

- Fixed 1920x1080 stage.
- Large type by default.
- One slide should have at most three columns or two rows.
- Prefer one central idea per slide.
- Use short Korean phrase lines with manual semantic breaks.
- Keep visible text sparse; move detail into speaker notes or presenter talk.
- Do not show slide numbers, total slide count, step count, or progress bars in the visible presentation.
- Do not expose internal sharing labels such as "company internal" on the slide canvas.
- Do not show dates on the slide canvas unless the user explicitly asks for a date.
- Do not use bottom-left footer notes or faint footer divider lines.
- Do not give one tile a different highlight color unless the user explicitly asks for a highlighted item.
- Cover slides should not use a top-left kicker; let the title stand alone.
- Closing slides should appear all at once and should not use a decorative top bar by default.

## Progressive Disclosure

- Slide changes use subtle transitions only.
- If a slide has separated parts, do not reveal them all at once.
- ArrowRight, Space, and PageDown reveal the next hidden part first.
- Only after all parts are visible should the deck move to the next slide.
- ArrowLeft and PageUp hide the current slide's last visible part before moving back.
- Use `data-step` for revealable fragments.

## Visual Style

- Background: warm white or very light neutral, not beige-heavy.
- Text: near-black charcoal.
- Accent: one restrained high-contrast color, preferably red-orange or green.
- Decorative elements should be structural and quiet: thin rules, stage numbers, small labels.
- Avoid cards-within-cards, decorative blobs, heavy gradients, and busy backgrounds.

## Typography

- Use a Google or Fontshare web font, never local system fonts.
- Recommended Korean font: `IBM Plex Sans KR`.
- Headline size: 92px to 132px.
- Body size: 42px to 58px.
- Small labels: 22px to 30px.
- Keep letter spacing at 0.

## Motion

- Slide transition: 260ms to 420ms fade with a tiny horizontal shift.
- Fragment transition: 220ms to 320ms fade and slight upward movement.
- Motion must feel calm, not dramatic.
- Include `prefers-reduced-motion` support.
