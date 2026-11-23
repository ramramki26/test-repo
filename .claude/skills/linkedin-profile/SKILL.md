---
name: linkedin-profile
description: >
  Writes Ramanan's LinkedIn profile (headline, About, Experience entry, Featured, banner line) so a
  founder who opens it after a DM trusts him enough to reply.
  Use when the user says "write my LinkedIn profile", "LinkedIn headline", "LinkedIn about section",
  "fix my LinkedIn".
user-invokable: true
argument-hint: "[current headline, About and Experience, pasted]"
license: MIT
metadata:
  author: Journals (adapted from Ootto bio-profile-optimizer)
  version: "1.0.0"
  category: content
---

# LinkedIn Profile — the page a founder checks before replying

Ramanan doesn't post on LinkedIn. His profile has one job: a D2C founder gets a DM from him, clicks
his name, and decides in about five seconds whether he's worth a reply. Read `journals-voice.md`
first; its rules override anything here.

## What you'll need
His current headline, About, Experience entries and Featured items (pasted), and whether a Journals
company page exists on LinkedIn.

## Instructions

1. **HEADLINE** (up to 220 characters; the first ~60 show next to his name in a DM, so they matter most).
   Say who he works with and what Journals does for them, at scale. Give 3 options. Example shape:
   "Co-founder, Journals | AI-native accounting for D2C brands doing ₹10cr+ | Books closed sooner,
   marketplace payouts reconciled". No "CEO", no "helping brands scale", no emojis.
2. **ABOUT** (the first ~3 lines show before "see more"; write those for the founder who stops there).
   - Lines 1–3: who it's for and the problems that show up at their size (several marketplaces, payouts
     that don't match orders, month-end dragging, no clear profit per channel or SKU).
   - Then where the credibility comes from: "my co-founder, a CA who has run his own firm for 5+ years,
     with clients from ₹5cr to ₹500cr". Journals is that firm, rebuilt to deliver with AI. Ramanan is the
     business-side co-founder and doesn't claim to be the finance expert.
   - Then what he's doing now: talking to D2C founders about where their accounting hurts.
   - End: "If that's you, message me." Nothing else. No booking link, no offer.
   - 120–200 words. First person. No bullet-point lists of services.
3. **EXPERIENCE:** Journals as the current role ("Co-founder", getjournals.ai), linked to the Journals
   company page if it exists (if not, say it should be created first: a person-only entry looks thin).
   Two or three plain lines, same message as the About. Past roles: leave as they are, no new detail.
4. **FEATURED:** getjournals.ai first. Nothing else unless it is real and specific (a dashboard
   screenshot, a page on the site). No posts to feature yet.
5. **BANNER:** one line of text, readable on a phone, e.g. "Accounting for D2C brands, built with AI and
   CAs." Plus the site URL.
6. **THE 5-SECOND TEST:** a ₹40cr D2C founder on four marketplaces opens the profile from a DM. Write what
   they'd conclude. If it isn't "this person works with brands like mine, and there's a CA firm behind
   him", fix the headline and the first lines of About.
7. Run every line through the `humanizer` skill before it's final.

## Before he saves
Remind him: turn off "Share profile updates with your network" (Settings → Visibility) before editing
anything.

## Never
- Name the co-founder or call him a relative.
- Invent clients, numbers or results, or claim personal years of accounting experience.
- Mention pilots, prices, cost savings, the WhatsApp bot or advisory.
- Mention past employers in the new copy.

**Next:** outreach drafts come from the LinkedIn agent in Journals OS (say "LinkedIn" in a new chat).
