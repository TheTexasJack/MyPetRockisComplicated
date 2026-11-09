# Comic Format & Strip Production | v1.0

**Project:** My Pet Rock Is Complicated  
**Status:** Creator-approved format, 2026-11-08.

## Primary publishing unit: one short comic strip

- **One strip = one complete publication unit**, containing **1 to 4 panels**, as required by the gag. Four panels is a *maximum*, not a mandatory template.
- Favor **short setups, sharp jokes, visual comedy, and character-driven payoffs**. No mandatory continuity homework for a reader encountering a strip out of order.
- A one-panel comic can be a complete visual punchline; two panels make a setup/payoff; three give setup/development/payoff; four allow one extra beat or reversal.
- **Occasional full-page spreads** are allowed as deliberately uncommon specials (a big reveal, epic absurdity, spectacular setting, or unusually strong visual joke). These are an exception, not the standard weekly production target.
- Keep the overall identity that of a **newspaper-style strip**, not default multi-page comic book issues.
- Preserve storytelling rhythm and readable dialogue. Silence is allowed; not every panel needs speech.

## Layout and publishing

- The canonical unit is the **strip**, not a fixed grid. A single row is the visual starting point, but final panel aspect ratios and device-specific arrangements should follow readability. A four-panel joke may still be one strip.
- **Exact dimensions, font, resolution, gutters, color profile, distribution, and mobile reflow rules remain open** until tested against approved art and the assembler. Do not silently hard-code them.
- Full-page specials use their own layout template and should still be archived as a single comic entry.

## Automation and reusable assets

- A strip's **Markdown script** is the source for dialogue, beats, character IDs, pose/expression references, prop bindings, panel order, and scene/environment selection.
- Claudia's future panel assembler can compose **approved reusable poses, props, environment layers, and lettered balloons** from that script.
- A generated or assembled strip is a **draft** until Nathan and Mara review panel readability, continuity, hands, accessories, attached props, layering, and comedic timing.
- Request unique artwork for scenes not covered by the reusable library; after approval, reusable new art can become an asset.
- The **artist-approved character model** governs anatomy and design across panels. Characters should not drift between 3+thumb and 4+thumb or silently gain costume changes.

## Story planning rule

Before production, choose the gag and its minimum effective panel count. **Do not stretch a one-panel joke into four panels just to fill a template.** Keep the special full-page format rare enough to feel special.

## Current scope

Primary: **1–4-panel strips**.  
Exception: **rare full-page spreads**.  
Deferred: longer-form issues, motion adaptations, and exact publishing/export specifications.
