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

## Outstanding (decisions blocked on missing assets)

### White-on-dark logo file

Brand Book Section 14 lists this as outstanding since 28 April 2026. Until the asset is in `/brand/logos/`, the following surfaces are BLOCKED and must not be produced with any substitute: document covers, section dividers, business card backs, dark hero website overlays.

The brand asset rule is absolute. The master JPG must not be colour-inverted. No synthesised SVG. No AI-generated version. Real asset or stop.

### Pantone reference

Brand Book Section 14 lists this as outstanding. To be settled in the Stationery and Document Standards v1.2 workstream. Until then, the CMYK values in brand-tokens.json are the print authority.
