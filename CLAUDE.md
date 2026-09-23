# CLAUDE.md

## Project
Client website starter — reusable base for clinic, restaurant, HVAC demos.
Each demo is a separate branch, then merged to main when ready.

## Stack
- Next.js 14+ (App Router) + TypeScript + Tailwind CSS
- Deploy: Vercel (auto-deploy from main)
- Forms: n8n webhooks (added per demo)

## Rules
- No extra libraries without asking first
- No databases, no auth, no Docker, no CMS
- Mobile-first: test every page at 375px width
- All components in /components
- All pages in /app
- Keep code simple — I need to read and edit it
- Use simple English in comments

## Gitgit add CLAUDE.md
- main = live site, never push directly
- Branch naming: feature/clinic-demo, fix/mobile-nav
- Always PR to main, never direct push

## Design
- Clean, modern, minimal — no clutter
- Max 2 fonts, max 3 colors per demo
- Every section needs good spacing (padding/margin)
- Images use Next.js Image component with proper alt text