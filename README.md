<h1 align="center">greps.net</h1>

<p align="center"><strong>Find unregistered domains — across every TLD, at scale.</strong></p>

<p align="center">
Check a single name across 35 TLDs instantly, or sweep thousands of candidates at once
against the official IANA RDAP registry. Pay-as-you-go, no subscription.
</p>

![greps.net](docs/screenshots/landing.png)

> **This is a public showcase of the project.** It's here to show what greps.net does — the
> application source itself is private.

---

## What it is

greps.net is a domain-availability scanner built for people who buy and brand domains.
Instead of checking names one at a time, you point it at a wordlist and it verifies
availability across your chosen TLDs using **RDAP** — the registries' own authoritative
protocol, not scraped WHOIS or guesswork — then scores and prices every hit so the good
ones rise to the top.

## Features

- **Instant check** — one name across 35 TLDs in a keystroke.
- **Bulk scans, eight ways** — Wordlist, Add-on (prefix/suffix), Letters, Numbers, TLD
  Swap, Phonetic, Domain Hack, and Leet. Glue two wordlists together for `word + word`
  brandables.
- **39 built-in wordlists** — Nouns, Verbs, Adjectives, Animals, Colors, Gemstones,
  Astronomy, Brand Morphemes and more — plus upload your own.
- **Authoritative availability** — every check goes to the official IANA RDAP registry, so
  "available" actually means available.
- **Scored & valued** — each result gets a brandability score and an estimated resale value.
- **Manage the pipeline** — filter, search, sort and export (CSV / JSON); re-check any
  result via RDAP; star favorites; keep a watchlist that emails you the moment a taken
  domain frees up; and track buys and sells in a portfolio.
- **Pay-as-you-go** — $5 = 10,000 lookups. No subscription, no card to start.

## A look inside

### Configure a scan
Eight scan types, a target-TLD picker, and a live credit estimate before you commit.

![Configure a scan](docs/screenshots/scan.png)

### Work the results
Every candidate, scored and priced — filter by length, TLD, score or scan, then export or
re-check in bulk.

![Results](docs/screenshots/results.png)

### Wordlists
39 curated system lists to scan against, plus your own uploads.

![Wordlists](docs/screenshots/wordlists.png)

## Built with

Laravel · Inertia · React · TypeScript · Tailwind CSS · RDAP · MariaDB · Redis

---

<p align="center"><sub>© 2026 greps.net · Showcase repository — application source is private.</sub></p>
