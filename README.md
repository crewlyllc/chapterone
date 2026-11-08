# ChapterOne

**A chapter-first platform for serial fiction.** Publish one chapter at a time, build a readership that comes back for the next one, and keep your mailing list yours.

Live site → **https://crewlyllc.github.io/chapterone/**

---

## Why chapter-first

Serial fiction doesn't fail because the writing is bad. It fails because the *format* fights the reader:

- A 90,000-word manuscript dropped in one file gets no second visit. A chapter that ends on a hook gets a subscriber.
- "Followers" on a big platform are rented. You can't email them, and the algorithm can decide tomorrow that you don't exist.
- Writers end up maintaining a story, a spreadsheet of readers, and a mailing list in three different places.

ChapterOne is built around the unit that actually drives retention: **the chapter**.

## What the platform does

**For writers**
- Create a series, then add chapters over time — each with its own title, order, and publish state.
- Draft privately, publish when the chapter is ready. No bulk import ritual.
- A public series page that reads well on a phone, with next/previous chapter navigation.
- Reader signups are collected for *your* series, not pooled into someone else's feed.

**For readers**
- Follow a series and get told when a new chapter lands.
- Read in order, pick up where you left off, no app install.
- Free sample chapter, no signup required: **https://crewlyllc.github.io/chapterone/read.html**

## Status

Private beta. The core loop — auth, series CRUD, chapter CRUD, reader flows — is built and running on Next.js + Prisma. Access is being opened in small batches so early writers get real attention instead of a number in a queue.

- **Readers** — join the waitlist: https://crewlyllc.github.io/chapterone/waitlist.html
- **Writers** — the creator waitlist asks what you're serializing and how often you publish, so onboarding starts from your story, not a blank dashboard.

## Stack

Next.js (App Router) · TypeScript · Prisma · PostgreSQL · Tailwind. Server-rendered reading pages, because chapter pages should load instantly on a phone with two bars of signal.

## Free sample

Chapter one of *The Signal Keeper* is readable right now, with no account:
**https://crewlyllc.github.io/chapterone/read.html**

---

*ChapterOne is an independent project. Not affiliated with Wattpad, Royal Road, Substack, or any other platform named in comparisons.*
