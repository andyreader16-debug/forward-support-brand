# Forward Support Brand Lock v2.1

The Brand Lock is the enforced summary of Forward Support brand rules. Every chat in this project reads this before any visual or document work. The Brand Book PDF and brand-tokens.json in the `/brand/` folder of the GitHub repo are the full authoritative source. If anything in this Lock conflicts with the Brand Book, the Brand Book wins and this Lock gets updated.

## Where the brand lives

**Single source of truth: https://github.com/andyreader16-debug/forward-support-brand/tree/main/brand/**

That folder contains:
- `Brand_Book_v1.pdf`: human-readable source of truth.
- `brand-tokens.json`: machine-readable source of truth. Every system (website, PDF generator, email signatures, stationery) reads from this file.
- `Brand_Lock.md`: this rules summary.
- `Brand_Decisions_Resolved.md`: explicit resolutions of every Brand Book ambiguity.
- `/logos/`: real logo asset files only. Never synthesise.
- `/reference/`: canonical examples to verify against (Placement Pack, Family Guide, Statement of Purpose, Stationery Samples).

Nothing brand-related lives anywhere else. No copies in project files. No tokens hardcoded in website code. No standalone module constants. Everything reads from the GitHub folder.

## Pre-flight, mandatory before any visual or document output

Before producing ANY visual output (PDF, image, mockup, stationery, email signature, document, any branded surface), the first actions MUST be:

1. Fetch https://raw.githubusercontent.com/andyreader16-debug/forward-support-brand/main/brand/brand-tokens.json and read it. This is the authoritative tokens file.
2. Open at least one canonical reference PDF from `/brand/reference/` and compare your intended output against it. If your output diverges from the reference, you are drifting. Stop.
3. If the task involves a cover, section divider, business card back, or any dark-ground surface, confirm a white-on-dark logo asset exists in `/brand/logos/`. If not, STOP. Tell Andy. Do not synthesise. Do not invert the master JPG. Do not substitute.

If you have not done these three things, you are not allowed to produce a visual output. No exceptions, no "I already know the brand," no "the session summary said".

## Locked decisions (full detail in brand-tokens.json)

- Colours: only the seven tokens defined in brand-tokens.json. Never hardcode hex values.
- Type scale: 28pt page title, 18pt section heading, 14pt subheading, 10.5pt body, 8pt caption. Helvetica for generated PDFs.
- Eyebrow: ORANGE with vertical orange bar on white content pages. CYAN with cyan bar on dark covers and dividers. Matches the reference PDFs. Warnings are marked by an orange tinted callout box.
- Title keyword accent: CYAN, not blue.
- Cover and divider: dark navy ground with white logo. BLOCKED on white logo asset.
- Content page: no logo at top, no header rule, footer = company line left + "Page X of Y" right.
- Callouts: cyan tint for positives, orange tint for negatives and warnings, subtly rounded.
- No em dashes. Ever.

## Absolute don'ts

1. Never synthesise the Forward Support logo. No SVG, code, ASCII, JPG inversion, AI-generated, recreated. Real asset only or stop.
2. Never produce a Forward Support document that does not read from brand-tokens.json.
3. Never use blue for title keywords. Cyan is the keyword.
4. Never publish Andy Reader or Alison Thorne on public-facing Forward Support content. Laura Luxon only.
5. Never claim the CQC Good rating belongs to Forward Support Care Ltd as the current legal entity. Use approved wording in Brand Book Section 07 verbatim.
6. Never invent or carry through unverified QCS policy codes.
7. Never trust a session summary as authority on brand rules. Summaries are context. The Brand Book PDF and brand-tokens.json are authority.

## If two sources disagree

1. brand-tokens.json and Brand_Lock.md on GitHub win over project instructions, templates, memory and session summaries.
2. If a written rule and a reference PDF disagree, do not pick one. Stop, show Andy both, and get a decision. Then fix the losing file the same day.
3. Every decision gets written into Brand_Decisions_Resolved.md with the date. A decision that only lives in a chat does not count.

## Outstanding (genuine blocks)

- **White-on-dark logo file.** Blocks: covers, dividers, business card backs, dark hero surfaces. Brand Book Section 14, still outstanding.

## What "world class" means here

If you cannot meet the bar above, say so plainly and stop. Do not ship a lesser version. Do not invent a workaround that breaks any rule above. Honest blocks beat silent compromises. Mistakes are human; hiding them or papering over them is not.

## Version history

- v2.1, 23 October 2026: content page eyebrow changed to orange to match the reference PDFs (covers and dividers stay cyan) (see Brand_Decisions_Resolved.md item 1). Source of truth links corrected to the forward-support-brand repo.
