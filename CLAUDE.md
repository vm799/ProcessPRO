# v-business-website — ICM Layer 2

## PERSONA
Brand website for Process Pro AI & Automation Solutions.
Single-file static site (index.html). Deployed on Vercel. Domain: processpro.uk.

## STAGE
Production. Live.

## REFERENCE
- `index.html` — entire site (HTML + CSS + JS, single file)
- GitHub: vm799/ProcessPRO
- Vercel: auto-deploys on push to main
- SSH remote: `git@github-vm799:vm799/ProcessPRO.git`

## SITE STRUCTURE (nav order)
1. Hero — headline + CTAs
2. Services (#services) — 6 service cards
3. Process (#process) — 4-step how we work
4. Work (#work) — 6 portfolio project cards
5. About (#about) — bio + stat blocks + tags
6. Contact (#contact) — cal embed + email

## KEY DETAILS
- Cal.com booking: https://cal.com/vaishali-gor-processpro/15min
- Email: vaishaligor25@gmail.com
- Cal embed: inline month_view, calLink = "vaishali-gor-processpro/15min"
- Design system: dark bg, accent cyan (#4ae3e3), mono font for labels/tags

## CONSTRAINTS
- Will NOT use a second GitHub account to push — must use vm799 via git@github-vm799
- Will NOT add external dependencies (no npm, no frameworks — stays single-file)
- Will NOT fabricate portfolio items — only add projects that exist in /repos
- Design changes must match existing card/border/mono-label pattern
