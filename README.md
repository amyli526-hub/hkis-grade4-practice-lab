# HKIS Grade 4 Admissions Practice Lab

A single-file, offline practice tool that simulates the computer-adaptive pre-entry assessment used for Grade 3–5 applicants at Hong Kong International School (HKIS): adaptive reading, language usage, and mathematics sections, plus a writing prompt and oral language practice.

**Open `index.html` in any modern browser.** No install, no build step, no network requests.

## What's inside

- **160+ multiple-choice items** across 13 skills (vocabulary, literary/informational text, mechanics, parts of speech, grammar, writing process, number sense, operations & fractions, algebra & patterns, geometry, measurement, data & probability)
- **Adaptive engine** — ELO-style ability estimate per subject (RIT scale, 160–250) plus an EWMA mastery score per skill; weak skills are weighted more heavily when picking questions
- **Instant feedback** with explanations, then a per-skill report and estimated RIT / percentile
- **Mock exam** — full 150-minute simulation: Reading → Language → Math → Writing prompt → Oral language, with automatic end on timeout
- **Writing studio** — six prompts (narrative / opinion / informational), 25-minute timer, checklist, model responses
- **Speaking practice** — 8 prompts, optional mic recording (MediaRecorder), self-rating
- **Progress report** — skill mastery bars, RIT trend sparkline, session history, day-by-day countdown to test day, JSON export, print-friendly layout
- **Persistence** via `localStorage`; nothing leaves the machine

## Notes

- RIT values and percentiles are **practice approximations**, not official NWEA scores. The tool is not affiliated with HKIS or NWEA.
- Item difficulties and the ability model are heuristic, hand-set values used to drive question selection.
- Question content is original and written against publicly described Grade 4 skill expectations.

## Structure

```
index.html                        # the whole app (HTML + CSS + JS, ~130 KB)
hkis-grade4-practice-lab.html     # identical copy, kept under the original filename
```

## License

Personal/educational use. No warranty.
