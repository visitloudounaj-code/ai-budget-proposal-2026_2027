# Visit Loudoun — Budget Proposal Presentations

HTML presentation pages built for internal budget proposals. Designed to be opened directly in a browser — no build process, no dependencies, no server required.

---

## Files

| File | Description |
|------|-------------|
| `AI-Tools-Budget-Proposal.html` | FY2026 proposal for a $1,000 AI tools and subscriptions budget |
| `conference-investment-proposal.html` | 2026–2027 professional development proposal covering seven industry conferences |

---

## How to View

Clone the repo and open either file directly in a browser:

```bash
git clone https://github.com/[your-username]/[repo-name].git
cd [repo-name]
open AI-Tools-Budget-Proposal.html
```

Or just double-click either `.html` file in your file explorer. No local server needed.

---

## AI Tools Proposal

**Ask:** $1,000 annual budget for AI tool subscriptions and emerging tool evaluation.

**What's covered:**
- Perplexity Pro — real-time cited research and fact-checking ($200/yr)
- Gemini Pro — Google Workspace integration ($240/yr)
- Picryl Premium — public domain image access from Library of Congress, Smithsonian, National Archives ($120/yr)
- Emerging tools testing — travel and tourism AI evaluation (~$440)

**Key argument:** Claude is already covered through the organization's AI coursework and will likely move to a Claude Enterprise subscription. This budget funds the complementary tools a single enterprise platform can't replace — specifically live sourced research, Google Workspace integration, public domain imagery, and the flexibility to evaluate new travel/tourism AI tools as they emerge.

---

## Conference Investment Proposal

**Ask:** ~$23,000–$25,000 across the 2026–2027 cycle for seven targeted industry events.

**Format:** Tabbed single-page layout — one tab per conference plus an Executive Summary. Tabs are driven by vanilla JavaScript with no external dependencies.

**Conferences covered:**
1. ESTO — Philadelphia, PA (Aug 2026)
2. brightonSEO San Diego — San Diego, CA (Sep 2026)
3. Skift Data + AI Summit — New York, NY (Jun 2026)
4. Digital Travel Summit — Orlando, FL (Sep 2026)
5. Phocuswright Conference — Hollywood, FL (Nov 2026)
6. DI Marketing & Communications Summit — Miami, FL (Feb 2027)
7. Simpleview Summit — TBD (2027)

---

## Brand

Both files use the Visit Loudoun brand color palette:

| Token | Hex | Use |
|-------|-----|-----|
| DeepMerlot | `#77092E` | Primary accent, hero backgrounds, headings |
| EarthyNoir | `#3E495B` | Dark sections, table headers |
| BoldSage | `#7B8F86` | Accents, borders, dividers |
| BlondeAle | `#D5BC5F` | Callout highlights, stat numbers |
| MorningSun | `#F0E9CC` | Section backgrounds, card fills |
| DogwoodBlush | `#EEE4DA` | Alternating section backgrounds |
| SaddleStitch | `#1E2322` | Body text, footer |

Fonts: **Lora** (serif headers) loaded via Google Fonts, with Georgia as fallback. **Arial** for body copy.

---

## Notes

- Both files are self-contained — all CSS and JS is inline. No external stylesheets or scripts beyond Google Fonts.
- Responsive breakpoints are included for mobile viewing.
- For print: the conference proposal includes a `@media print` rule that expands all tabs and hides navigation.
- Cost figures in both proposals are directional estimates and should be confirmed before submission.

---

*Prepared by AJ Mirabal, Marketing Coordinator — Visit Loudoun*
