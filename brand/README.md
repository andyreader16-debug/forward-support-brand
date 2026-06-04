# Forward Support Brand

**This folder is the single source of truth for the Forward Support Care Ltd brand. Every system reads from here. Nothing brand-related lives anywhere else.**

## What's in here

| File | What it is | Who reads it |
|---|---|---|
| `Brand_Book_v1.pdf` | The brand, human-readable. | People. |
| `brand-tokens.json` | Colours, type scale, all values, machine-readable. | Website, PDF generator, email signatures, stationery. |
| `Brand_Lock.md` | Rules summary. The enforced bit that every Claude chat reads. | Claude, anyone editing brand assets. |
| `Brand_Decisions_Resolved.md` | Each Brand Book ambiguity given a single answer. | Anyone making a decision. |
| `/logos/` | Real logo asset files. Never synthesise. | Every document and surface that uses the logo. |
| `/reference/` | Canonical example PDFs to verify against. | Anyone building a new document. |

## How to use it

**If you are editing the brand:** change the relevant file here, commit, push. The website rebuilds. The next PDF generated picks up the change. Everything stays in sync because nothing else has its own copy.

**If you are reading the brand:** open `Brand_Book_v1.pdf` for the human version, or `brand-tokens.json` if you need the values.

**If you are building a new document:** read `Brand_Lock.md` first. Then look at the relevant PDF in `/reference/`. Then build.

## What NOT to do

- Do not put a copy of the brand elsewhere (project files, local computer, another repo) and treat it as authoritative. Local copies are mirrors, not sources.
- Do not hardcode brand values (hex codes, font sizes) in any system. Read from `brand-tokens.json`.
- Do not synthesise the logo. Ever.
- Do not edit a copy of the Brand Book somewhere else and expect this folder to update.

## Outstanding

The white-on-dark logo variant is outstanding (Brand Book Section 14). When it arrives, it goes in `/logos/` and the covers/dividers/business card backs become buildable.

## Version

Brand_Book_v1.pdf is version 1.0, 28 April 2026.
brand-tokens.json is version 1.0, last updated 3 June 2026.
Brand_Lock.md is version 2.0.
