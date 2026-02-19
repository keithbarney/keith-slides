# Keith Slides

Interview presentation deck for Keith Barney — Design Systems Lead.

## Contents

| File | Description |
|------|-------------|
| `slides.html` | Main presentation deck — 27 slides covering career overview and 5 case studies with keyboard/touch navigation, slide menu, and animated halftone background |
| `resume.html` | Standalone HTML resume with responsive 12-column grid layout and print styles |
| `case-studies.html` | Case study prep document (3 studies with problem/ownership/impact framework) |
| `case-studies-prep.md` | Raw case study notes from mentorship sessions |
| `self-assessment.md` | Strengths/weaknesses self-assessment |
| `mentorship-log.md` | Session notes from portfolio mentorship with Andrew Johnson |

## Usage

No build step required — open any `.html` file directly in a browser.

```sh
open slides.html
```

### Slide Navigation

- **Arrow keys** / **Space** / **Enter** — next slide
- **Backspace** — previous slide
- **Home** / **End** — first / last slide
- **Click** — left third goes back, right two-thirds goes forward
- **Swipe** — touch navigation on mobile
- **Menu button** — jump to any section
- **Escape** — close menu

## Fonts

Custom fonts are stored in `src/assets/fonts/`:
- Test American Grotesk (Regular, Medium, Bold)
- JetBrains Mono (Regular)

## Note

`slides.html` references an external design system CSS (`heavy-design-system`). The presentation uses inline styles as fallback and works standalone, but some token-based styles (CSS custom properties like `--ui-bg-default`) require the design system for full rendering. The halftone background and all slide layouts are self-contained.
