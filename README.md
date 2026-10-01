# BYUI Pre-Med Course Guide — V3

A polished static prototype for the next version of the BYUI Pre-Med planning platform.

## Included now
- Redesigned responsive homepage and unified design system
- About and Trust & Transparency pages
- Course browser with search, subject filters, MCAT filters, sorting, and BIO 240 Neurobiology
- Rich course detail pages that become more informative as approved ratings accumulate
- Streamlined rating form and moderation prototype
- Rebuilt Path Planner with 4 years, drag/drop pre-med courses, manual religion/GE/elective/major courses, total credit + workload estimates, planning targets, alternate-plan copy, autosave, and print/PDF support
- Dashboard connected to saved planner data
- Road to Medical School overview
- Resources/Future Tools page
- YouTube footer link
- Reduced-motion support and responsive layouts

## Important production notes
This is still a static GitHub Pages-compatible build. Planner/review data uses browser localStorage. It intentionally does **not** fake secure authentication. Before public production use, move accounts, reviews, moderation, planner data, and experience tracking to a real backend with authenticated authorization (for example Supabase or another appropriate service).

Course catalog facts in this prototype are not guaranteed current. Verify course numbers, titles, credits, prerequisites, offering patterns, and MCAT mappings against official/current sources before representing them as authoritative.

## Deploy
Upload the contents of this folder to the root of the existing GitHub repository and commit to `main`. GitHub Pages can continue deploying from `main / (root)`.
