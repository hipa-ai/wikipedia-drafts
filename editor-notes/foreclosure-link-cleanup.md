# Foreclosure — external-link / citation cleanup

**Target:** https://en.wikipedia.org/wiki/Foreclosure (live article — direct "Edit source")
**Type:** Cleanup of three junk citations. NOT a draft and NOT an AfC submission.
**Date prepared:** 2026-05-28

Three references in the live *Foreclosure* article are spam / dead / self-published
blogs that fail WP:RS and add no encyclopedic value. None of them are in the
formal `== External links ==` section — all three are inline `<ref>` citations.

How to apply: open the article → **Edit source** → find each snippet below →
remove as described → save with the suggested edit summary. These are three
independent edits; you can do them in one save or three.

---

## 1. Big Door Homebuyers — promotional spam  (section: *Contesting a foreclosure*)

A commercial "we buy houses" lead-gen company was inserted into the article
body, sourced to its own marketing page. Added recently (`access-date=2025-12-16`).
Fails WP:PROMO, WP:SPAM, and WP:RS (self-published promotional source).

**Remove the two sentences AND the citation** — everything from "Some companies"
through the closing `</ref>`:

```
Some companies, such as '''Big Door Homebuyers''' offer foreclosure prevention services, providing homeowners facing financial difficulties with options such as cash home sales to avoid foreclosure. These services may provide an alternative solution for those seeking to avoid the legal complexities of the foreclosure process.<ref>{{cite web |title=Stop Foreclosure |url=https://bigdoorhomebuyers.com/stop-foreclosure/ |website=Big Door Homebuyers |access-date=2025-12-16}}</ref>
```

**Keep** the legitimate sentence immediately before it ("Occasionally, borrowers
have raised enough cash at the last minute … preserved their rights to challenge
the foreclosure process.").

Edit summary: `rm promotional content + self-published source for "Big Door Homebuyers" (WP:PROMO, WP:RS)`

---

## 2. Block Colorado Foreclosure Blog — dead link + blog  (section: *Contesting a foreclosure*)

Bare-URL citation to a self-published blog. The site is fully dead (connection
refused), and there is no usable archive. WP:SPS + WP:DEADLINK.

**Remove this bare ref:**

```
<ref>Block Colorado Foreclosure Blog http://www.blockcoloradoforeclosure.com</ref>
```

If removing it leaves a sentence with no other citation, that is fine — a dead
blog was never a valid source. Optionally add `{{citation needed|date=May 2026}}`
in its place if the supported claim should stay.

Edit summary: `rm dead self-published blog citation (blockcoloradoforeclosure.com; WP:SPS, dead link)`

---

## 3. 4506-transcripts.com blog — self-published source  (section: *Recent trends*)

A tax-transcript vendor's corporate blog, cited for 2014 RealtyTrac foreclosure
statistics. The blog is not a reliable source (WP:SPS); it merely repeats
RealtyTrac numbers secondhand. There is a 2014 web.archive snapshot, but
archiving an unreliable source does not make it reliable.

**Remove this citation:**

```
<ref>{{cite web|url=http://blog.4506-transcripts.com/2014/09/22/housing-market-recovery-myth-or-reality/|title=Housing Market Recovery: Myth or Reality|date=22 September 2014|website=4506-transcripts.com|access-date=8 May 2018|url-status=live|archive-url=https://web.archive.org/web/20141014075637/http://blog.4506-transcripts.com/2014/09/22/housing-market-recovery-myth-or-reality/|archive-date=14 October 2014}}</ref>
```

The sentences it supports are now ~12-year-old statistics ("As per the
foreclosure data report of RealtyTrac for January 2014 … As of August 2014, the
foreclosure rate was 33.7% …"). Once the only source is removed they are
unsourced **and** stale. Recommended: **remove those stale stat sentences too.**
If you would rather keep them, tag with `{{citation needed|date=May 2026}}` —
but the cleaner fix is removal, since the "Recent trends" section is outdated.

Edit summary: `rm self-published blog source (4506-transcripts.com) and stale 2014 stats (WP:SPS)`

---

## Notes
- All three are inline references, so removing each `<ref>…</ref>` also drops its
  numbered entry from the reference list automatically.
- Big Door (#1) is the clearest violation — recently inserted promotional spam.
- This cleanup is unrelated to the hipa.ai drug-article link work; it is plain
  WP:RS / WP:SPAM housekeeping on a high-traffic article.
