# Forward Support — Brand

**What this repo is for:**
The single source of truth for how Forward Support looks. Every colour, font, logo, and brand rule lives here. Before producing any visual output — a PDF, a web page, a document — fetch from this repo first.

**What lives here:**
- `/brand/brand-tokens.json` — every colour, font size, and spacing value. This is the authority.
- `/brand/Brand_Lock.md` — the full brand rules. Read before any visual work.
- `/brand/Brand_Decisions_Resolved.md` — record of every contested brand decision and how it was resolved
- `/brand/reference/` — canonical reference PDFs showing exactly how documents should look
- `/brand/logos/` — logo files in all approved formats

**The most important rule:**
Never hardcode a colour value anywhere. Always fetch from `brand-tokens.json`.

**Current brand values:**
- Blue: `#004DB5`
- Orange: `#E8720A`
- Cyan: `#00B5CF`
- Grey: `#706F6F`
- Dark: `#060D22`

**Outstanding:**
- White logo file still needed for dark backgrounds, covers, and section dividers.

**Owner:** Andy Reader

---

**The three repos at a glance:**

| Repo | What it's for |
|---|---|
| [Website](https://github.com/andyreader16-debug/Forward-Support-Website) | Public website code and designs |
| [Internal](https://github.com/andyreader16-debug/forward-support-internal) | Running the business — docs, SOPs, governance |
| This one — Brand | How we look — logos, colours, brand rules |
