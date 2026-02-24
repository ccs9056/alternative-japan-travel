# Alternative Japan Travel

## Project Overview
A curated digital travel resource dedicated to crowd-avoiding, high-value alternatives in Japan. The platform guides travelers away from congested tourist traps toward legitimately rewarding, low-stress destinations, making trips genuinely enjoyable rather than exhausting.

## Target Audience
Travelers who have already completed the standard "Golden Route" or intentional planners seeking to avoid overtourism from the start. They prioritize mental bandwidth, authentic experiences, and a calmer pace over checking off crowded landmarks.

## Market Niche & Positioning
Positioned as the go-to curator for "The Great Exchange" in Japan travel. The site focuses on practical, one-to-one swaps (e.g., trading a congested temple district for an accessible, quieter regional equivalent). It differentiates through clean curation, emphasizing realistic logistics and high enjoyment over extreme "off-the-grid" travel.

## Core Value Proposition
- **Direct Swaps:** Practical, vetted alternatives to Japan's most overcrowded pain points
- **Accessibility:** Focus on lesser-visited destinations still highly accessible via standard transit (Kanazawa, Tohoku, Kyushu), removing the friction of deep-rural travel
- **Actionable Curation:** Simple, realistic tips on pacing, timing, and transit without overwhelming the user

## Monetization
- **Primary:** Contextual affiliate partnerships (regional transit passes, Rakuten Travel accommodations, curated local tours) seamlessly integrated into recommendations
- **Secondary:** Low-friction premium digital products (curated, downloadable regional itineraries)

## SEO & Growth Strategy
Capture intent-based, long-tail search queries centered on crowd avoidance and return-trip planning (e.g., "calmer alternatives to Kyoto," "Japan second trip ideas"). Build authority through focused, theme-based content clusters rather than scattered travel diaries.

---

## Technical Stack
- **Static HTML site** — no framework, no build step
- **Tailwind CSS** via CDN (`https://cdn.tailwindcss.com`)
- **Google Fonts** (Poppins) + **Font Awesome** icons via CDN
- **Vanilla JavaScript** only (no libraries)
- Placeholder images from `https://placehold.co/` until real assets are added

## Deployment
- **GitHub repo:** `ccs9056/alternative-japan-travel`
- **Live site:** `https://alternative-japan-travel.vercel.app`
- **Workflow:** Edit files locally → commit → push to GitHub → Vercel auto-deploys
- **Git auth:** Uses `gh` CLI for authentication (`gh auth setup-git`)

## Project Structure
```
index.html          — Homepage (single-page for now)
.gitignore          — Excludes videos, large media, internal docs
CLAUDE.md           — This file (project context for Claude Code)
design-reference.md — Design workflow for recreating pages from screenshots
```

## Design Guidelines
- Mobile-first responsive design
- Clean, modern aesthetic — not cluttered
- Video backgrounds and strong imagery where appropriate
- Brand color: `#E63946` (primary red), `#C62828` (dark variant)
- Font: Poppins (weights 300-800)
- The site should look polished and professional, but isn't overly complex

## Content Guidelines
- Always frame content as "swap X for Y" — the core differentiator
- Destinations must be accessible via standard transit (not deep-rural)
- Keep copy concise and actionable — no travel diary style
- Affiliate links should feel like natural recommendations, not ads

## Rules
- Only push files needed for the website to GitHub (no video files, no internal docs)
- Keep it simple — static HTML pages, no unnecessary tooling
- When adding new pages, follow the same Tailwind CDN + inline approach as index.html
- Ask before making major structural changes
