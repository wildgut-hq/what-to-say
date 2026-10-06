# WildGut — What To Say

Creator compliance and follower-FAQ reference. The page creators open when someone asks a health question in their comments.

Live page: https://wildgut-hq.github.io/what-to-say/

To update: edit `index.html`, commit, push to `main` — GitHub Pages redeploys automatically (~1 min).

Printable PDF (A4) — the page has a `@media print` stylesheet that force-opens every accordion, so the PDF contains all answers:

```
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless=new --disable-gpu --no-pdf-header-footer --print-to-pdf=what-to-say.pdf "file://$(pwd)/index.html"
```

## Sources of truth

Do not edit facts on this page from memory. Each comes from somewhere:

| Fact | Source |
|---|---|
| Pregnancy / breastfeeding not suitable | Live quiz disqualification screen, `web/wildgut-domain/screens/disqualification.html` |
| 11 ingredients, 60 vegan capsules, UK, GMP | `brand/guidelines.md` (updated 2026-08-17) |
| Dosing: start on 1/day, up to 2, 1/day long term | Humza, founder calls 2026-09-10 (supersedes the "2 a day" in the GLP-1 guide) |
| Core ingredients (10 of 11) | Humza, from the product label, 2026-10-06 |
| Ingredient mechanisms (rhubarb, aloe, glucomannan) | Humza, Salli founder call 2026-10-06 (Gemini transcript in Drive). Supporting-ingredient lines written conservatively: traditional use or simple fibre facts only |
| Banned words | `CLAUDE.md` non-negotiable rules |
| Say / don't-say table | `creators/glp1_creator_guide.html` section 6 |
| Violation history and the rename | Humza, founder calls 2026-09-10 |

## Open gaps

- **The 11th ingredient is not named.** The page lists the 10 core ingredients Humza gave from the label (2026-10-06) and calls them "the core ones". Confirm the 11th and add it if it should be listed.
- **Allergen positions beyond vegan** (gluten, dairy, specific intolerances) have no documented answer. Page routes these to Humza.
- **IBS and diagnosed conditions** have no brand position, so the page uses the safe default (send to GP). If a real position is wanted, it needs sign-off.
