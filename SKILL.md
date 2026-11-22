---
name: kdp-policy-verification-addon
description: Build and refresh a dated KDP policy index from current official Amazon sources for content, AI disclosure, metadata, ebook files, royalties, promotions, and exclusivity. Use before outlining/production decisions and again before final publishing-package preparation.
---
# KDP Policy Verification Add-on

Verify policy from official Amazon/KDP sources for the user's marketplace, format, territory, and intended publication date. This is a source-capture process, not legal advice. Memory, course materials, vendor blogs, and prior captures are not current-policy proof.

## Verification procedure
1. Record project title/ID, target marketplace, language, formats, territories, planned release window, and decisions this check must support.
2. Build a topic checklist for relevant rules: content/rights, AI-generated versus AI-assisted disclosure, metadata, categories/keywords, ebook file formats and quality, accessibility, royalties/pricing/territories, KDP Select exclusivity and promotions, and upload/preview requirements.
3. For each topic, open the current official source page. Record URL, exact page title, access timestamp and timezone, applicable marketplace/format, concise faithful rule summary, relevant quotation or section heading when useful, and unresolved ambiguity. Don't use search-result snippets as evidence.
4. If a rule depends on marketplace, VAT, file size, price, title format, or release option, record those exact project inputs. Never generalize a U.S. or one-format rule to all markets.
5. Classify each statement as `CURRENT VERIFIED RULE`, `PROJECT ASSUMPTION`, `THIRD-PARTY CLAIM`, `AUTHOR DECISION`, or `NOT VERIFIED`. Heuristics from the source workflow (such as competition thresholds) are not KDP requirements unless an official source explicitly says they are.
6. Compare against the previous capture. Record changed/removed rules, date, affected artifacts, impacted stages, required rework, and decision owner. Never overwrite old dated captures.
7. Apply freshness per decision. Honor the existing publish-package card's 30-day maximum; refresh immediately before final package approval. Recheck sooner if Amazon updates relevant policy or if a marketplace/format/price changes.
8. Capture the author's AI-use facts separately for text, images, and translations. Do not infer that AI was used or not used. Ask the author to resolve unknown provenance before preparing a disclosure answer.
9. If the official source is inaccessible or contradictory, mark that item `NOT VERIFIED`; block only the dependent decision and state exactly what source or human clarification is needed.

## Required output
Create `02_Knowledge_Base/KDP_POLICIES/POLICY_INDEX_<yyyymmdd>.md`. For every topic include source URL/title, capture timestamp, scope, rule summary, project-specific applicability, evidence status, prior-version delta, dependent canonical stages, and next action. Include an AI provenance/disclosure input section and a final verdict: `PASS`, `STALE`, or `BLOCKED`.

`PASS` means the captured set is sufficiently current and verified for its stated decisions; it does not mean Amazon approval. Do not upload, publish, enroll in Select, or change account settings.