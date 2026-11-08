# Media Production & Asset Workflow | v0.1

## Shared source of truth
- `docs/bible/` owns characters, relationships, world lore and approved facts.
- `docs/production/` owns style, roadmap, workflow and publishing checklist.
- `assets/images/` owns original references, layered/source files, approved masters, and derivative exports.
- `comics/`, `video/`, `audio/`, `other-media/` own each format's scripts, production plans and completed deliverables.

## Art workflow
1. Save raw art in `assets/images/source/` and identify origin/date.
2. Clean or adjust in GIMP or editor, including mandatory horizontal goat pupils for Optout.
3. Save creator-approved master in `assets/images/approved/` with a short note about why it is canonical.
4. Put optimized display images, crops and panel-sized versions in `assets/images/exports/`.
5. Record source/approved relationship in `assets/images/README.md`.

**Important:** Today's source graphics are not all uploaded yet. Keep an accurate inventory; never claim a working image is in GitHub unless it is actually there.

## Naming
- `characters/upshot/<purpose>_v01.png` when organizing a character inside an image subfolder; equivalent flat names okay for first pass.
- `comics/issue-001/script.md` and `comics/issue-001/storyboard.md`.
- `video/short-001/script.md` and `video/short-001/storyboard.md`.
- `audio/short-001/` for voice and sound work related to video short 001.
- Prefer lowercase, hyphenated filenames; preserve required character naming in metadata.
- Keep original layered masters when available. Use Git LFS for large binary assets if repository size starts becoming unwieldy.

## Script and asset linkage
Each comic or animation should state: title, logline, participants, continuity date/order, approved art references, dialogue, scene/panel list, and status.

## Release safety
Use authorized art, font, sound and music assets. Avoid distributing copyrighted third-party character imagery as standalone official media; keep the universe independent. Review any later public-facing website or software for XSS, injection, dependency and credential risks before shipping.

## Roles
- **Creator:** final editorial and design approval.
- **Collaborators/tools:** draft and propose; update only following review.
