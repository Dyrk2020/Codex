# CMU 11-768 — AI Agents (Fall 2026)

- Site: https://www.cmu-agents.com/ (saved: `index.raw.html` + SPA bundle `app.js`)
- Meta description: "11-768 AI Agents at Carnegie Mellon University (Fall 2026): a graduate course on LLM-based AI agents — tool use, planning, memory, training, safety, and interaction."
- Canvas (CMU-internal): https://canvas.cmu.edu/courses/55126

## Notes
- The site is a client-side React SPA; schedule/topic data renders from the JS bundle (`app.js`, saved). Static extraction found only one arXiv reference and external course-site links in the bundle; the full schedule page is behind the SPA's client router.
- Related CMU courses referenced from the same bundle: cmu-llms.org, cmu-codegen.github.io/f2025, cmu-l3.github.io/anlp-spring2026.

## Reproduce rendering (if needed)
`npx playwright screenshot https://www.cmu-agents.com/ cmu-agents.png --full-page` or open in browser; the schedule route lives under the SPA's `#schedule` hash route.