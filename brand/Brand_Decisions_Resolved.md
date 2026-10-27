# Forward Support Brand Decisions Resolved v1.1

The Brand Book v1.0 contains a small number of internal contradictions and ambiguities. This document resolves each one explicitly so no future chat has to make a judgment call. If you spot a contradiction not listed here, add it here with the resolution rather than making the call yourself.

## Resolved

### 1. Eyebrow colour: cyan or orange?

**Brand Book Section 04 text:** says "Cyan or Orange" (both allowed).

**Resolved:** CYAN is the default. Orange is reserved for negatives, warnings, gates, and "do not" callouts.

**Rechecked 23 October 2026:** the April 2026 reference PDFs used orange eyebrows on content pages. The live v2 Placement Pack and Family Guide, and every SOP build script, use cyan. Cyan confirmed. The April PDFs were moved to /reference/archive/ and replaced with the live v2 versions so the references match this rule.

### 2. Title keyword accent: cyan or blue?

**Source documents differ:** the Brand Book Section 11 says "key word in cyan." Some earlier drafts used blue.

**Resolved:** CYAN. This matches the Placement Pack ("A home **built around** the people who live here") and the Family Guide ("Moving to **Catherine House**") where the cyan keyword treatment is established as the brand pattern. Blue keywords are a drift pattern and not used.

### 3. Stationery footer rule: orange or grey?

**Brand Book Section 09 text:** "thin orange line above the footer."

**Brand Book Section 09 preview:** shows a thin grey rule, not orange.

**Resolved:** ORANGE per the Section 09 text. Preview is updated in the next stationery rebuild to match.

### 4. Business card back: navy or white?

**Brand Book Section 09 text:** "dark navy background, white logo centred, tagline in cyan."

**Brand Book Section 09 preview:** shows a white back with blue logo (because the white-on-dark logo asset is outstanding).

**Resolved:** NAVY per Section 09 text. The preview reflects the interim treatment while the white logo is outstanding. Business card backs are BLOCKED until the white logo is in `/brand/logos/`.

### 5. Content page chrome: with or without top logo and rule?

**Brand Book Section 11 written spec:** "small blue logo top-left, document reference top-right, thin blue rule below header."

**Existing audience PDFs (Placement Pack, Family Guide):** no logo, no top rule, just clean content from the top margin. Footer carries the identity.

**Resolved:** Follow the existing audience PDFs. No logo at the top of content pages. No header rule. Clean content from the top margin. Footer: company line left, "Page X of Y" right. This is the live canon and what every new document matches.

### 6. Page numbering style: "3" centred or "Page X of Y" right?

**Brand Book Section 11 text:** "page number centred."

**Existing audience PDFs:** "Page X of Y" right-aligned in the footer.

**Resolved:** "Page X of Y" right-aligned, per the existing audience PDFs.

### 7. Handwritten font: allowed or not?

**Context:** the Brand Lock says no decorative or script fonts. The 'Hi Sarah' QA pack (October 2026) used Caveat for a greeting, a sign-off and short asides, and Andy liked how it took the corporate edge off.

**Resolved 23 October 2026:** Caveat is allowed as a sparing accent only, as set out in brand-tokens.json handwrittenRules. It is not a body or heading font. The general ban on decorative fonts still applies to everything else.

### 8. Standalone forms: logo or no logo?

**Context:** content pages carry no logo at the top (decision 5). A standalone form, such as a cleaning sheet or a log on a clipboard, has no cover, so without a logo nothing on the page says whose form it is.

**Resolved 27 October 2026 (Andy):** standalone forms carry the blue logo top left, with the eyebrow and title below it. Multi-page documents keep decision 5.

### 9. Form row striping: which colour?

**Context:** Andy asked whether the striped rows on forms should be darker so they show up on the office printer.

**Resolved 27 October 2026 (Andy), after a print test:** alternating rows stay Tint #F5F7FB. The test sheet printed clearly, so no change.

### 10. Form table lines: which colour?

**Context:** Ali printed a form with no lines on it. The 04 draft forms had been built with #DCE2EC for table lines, which is not a brand colour and is too pale for the office printer.

**Resolved 27 October 2026 (Andy):** every table line, box outline and write-in rule on a form is Hairline #BFBFBF at 0.75pt or heavier. Nothing lighter than Hairline. Blue #004DB5 is allowed for an outer frame. All drafts in 04 were corrected the same day.

**Superseded the same day by decision 12.**

### 11. Form eyebrows: cyan, as everywhere else

**Context:** several 04 draft forms were built with orange eyebrows and orange section labels, against decision 1.

**Resolved 27 October 2026 (Andy):** form eyebrows and section labels are cyan with the cyan bar, the same as every other document. Orange stays for warnings, gates and the negative half of a pair (for example the "Needs picking up" table header on D.01). All drafts in 04 were corrected the same day.

### 12. Form lines: dark grey, so they survive photocopying

**Context:** after decision 10, forms printed from a computer or phone showed their Hairline #BFBFBF lines, but photocopies of them came out with the lines almost gone. Staff will photocopy a form when the folder runs low, however the rule is written.

**Resolved 27 October 2026 (Andy), after a mock-up comparison:** every table line, box outline and write-in rule on a form is Grey #706F6F at 0.75pt or heavier. Blue #004DB5 stays allowed for an outer frame. Row striping stays Tint #F5F7FB. Live forms move to v1.1 with this change only. Staff still print from the shared drive rather than photocopying where they can (E.01), because a photocopy can be an old version.

### How these are enforced

Every form is checked with `scripts/brand_check.py` in forward-support-internal before it is shown to anyone or moved into "02 Forms in use". It flags lines lighter than Grey #706F6F or thinner than 0.75pt, colours that are not in brand-tokens.json, orange eyebrows, blue title keywords and em dashes. A form that fails is not finished.

## Outstanding (decisions blocked on missing assets)

### White-on-dark logo file

Brand Book Section 14 lists this as outstanding since 28 April 2026. Until the asset is in `/brand/logos/`, the following surfaces are BLOCKED and must not be produced with any substitute: document covers, section dividers, business card backs, dark hero website overlays.

The brand asset rule is absolute. The master JPG must not be colour-inverted. No synthesised SVG. No AI-generated version. Real asset or stop.

### Pantone reference

Brand Book Section 14 lists this as outstanding. To be settled in the Stationery and Document Standards v1.2 workstream. Until then, the CMYK values in brand-tokens.json are the print authority.
