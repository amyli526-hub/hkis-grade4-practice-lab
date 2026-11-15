# HKIS Grade 4 Admissions Practice Lab

A single-file, offline practice tool that simulates the computer-adaptive pre-entry assessment used for Grade 3–5 applicants at Hong Kong International School (HKIS): adaptive reading, language usage, and mathematics sections, plus a writing prompt and oral language practice.

**Open `index.html` in any modern browser.** No install, no build step, no network requests.

## What's inside

- **249 multiple-choice items** (including four long passages with 4-5 questions each and 55 items at RIT 220+) across 13 skills (vocabulary, literary/informational text, mechanics, parts of speech, grammar, writing process, number sense, operations & fractions, algebra & patterns, geometry, measurement, data & probability)
- **Adaptive engine** — ELO-style ability estimate per subject (RIT scale, 160–250) plus an EWMA mastery score per skill; weak skills are weighted more heavily when picking questions
- **Hint and second try** on a wrong answer (only the first attempt is scored), then the explanation; answer choices are shuffled on every display
- **Mistake list** — missed items return in a review set until answered correctly twice
- **Per-skill report** with an estimated RIT (no percentile: the tool has no official norm data)
- **Mock exam** — untimed simulation with an elapsed-time clock: Reading → Language → Math → Writing prompt → Oral language
- **Writing studio** — six prompts (narrative / opinion / informational), 25-minute timer, checklist, model responses, 5-row parent scoring guide (out of 20)
- **Speaking and interview practice** — 18 prompts (8 speaking, 10 interview) with follow-up questions, parent guidance, optional mic recording (MediaRecorder), 7-row rating guide
- **Progress report** — skill mastery bars, RIT trend sparkline, session history, day-by-day countdown to test day, JSON export, print-friendly layout
- **Persistence** via `localStorage`; nothing leaves the machine

## Notes

- RIT values and percentiles are **practice approximations**, not official NWEA scores. The tool is not affiliated with HKIS or NWEA.
- Item difficulties and the ability model are heuristic, hand-set values used to drive question selection.
- Question content is original and written against publicly described Grade 4 skill expectations.

## Structure

```
index.html                        # the whole app (HTML + CSS + JS, ~175 KB)
hkis-grade4-practice-lab.html     # identical copy, kept under the original filename
```

## License

**Public domain — CC0 1.0 Universal.** This work is dedicated to the public
 domain; the author has waived all copyright and related rights worldwide.
 You may copy, modify, distribute, and use it for any purpose, including
 commercial use, without asking permission and without attribution.

See [LICENSE](LICENSE) for the full legal code.

Third-party names (HKIS, NWEA, MAP) remain the trademarks of their respective
owners and are not covered by this dedication.
