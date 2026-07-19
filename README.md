# cloud-itonami-lei-254900em62y5rrtj9771

> **Independent third-party archive/analysis. Not affiliated with, endorsed by, or sponsored by SBS Transit Ltd.**

This repository archives the publicly published Conditions for Use of **SBS
Transit Ltd**, with source-url and retrieval-date provenance, per
[ADR-2607110300](https://github.com/com-junkawasaki/root/blob/main/90-docs/adr/2607110300-cloud-itonami-lei-corporate-tos-catalog.edn)
(`cloud-itonami-lei-corporate-tos-catalog`, `com-junkawasaki/root`). It is a read-only
reference/archive repository — it does not act, propose, or execute anything on the
company's behalf, and is not a governed Advisor/Governor actor.

## Company identity

- **Legal name**: SBS Transit Ltd
- **LEI (ISO 17442)**: [254900EM62Y5RRTJ9771](https://search.gleif.org/#/record/254900EM62Y5RRTJ9771) (GLEIF-verified; entity status ACTIVE; LEI **registration status LAPSED** — recorded honestly, not glossed over)
- **Jurisdiction**: SG (Singapore)
- **Website**: https://www.sbstransit.com.sg
- **Ticker**: SBTL (SGX); 75%-owned by ComfortDelGro Corporation Limited (already archived at `cloud-itonami-lei-2549005o5pva2jch6q33`)

## Contents

- `80-data/public/tos.journal.edn` — EDN quad-log of archived Conditions for Use documents.
- `NOTICE` — copyright/attribution statement for the archived third-party text.
- `blueprint.edn` — machine-readable company identity record.

## Related cloud-itonami blueprint (passenger-road-transport vertical)

SBS Transit is Singapore's largest public bus operator (also operating rail
services). This vertical's *generic, forkable* Open Business Blueprint
counterpart in the `cloud-itonami` fleet is
[`cloud-itonami-isic-4921`](https://github.com/cloud-itonami/cloud-itonami-isic-4921)
(ISIC 4921/4922 sibling pair — urban/suburban vs. intercity/chartered coach
scheduling-and-dispatch coordination, Advisor⊣Governor actor pattern). This
LEI-catalog entry is a **read-only ToS reference only** — it is not a fork of, and
has no code dependency on, isic-4921; the cross-reference exists so a reader
researching real-world urban-bus operators for market/competitive context can find
both the real company's published terms and the corresponding generic
governed-actor blueprint from one place. This is a distinct legal entity from its
parent ComfortDelGro (already archived, `cloud-itonami-lei-2549005o5pva2jch6q33`),
not a duplicate.

## Design rationale

See ADR-2607110300 in `com-junkawasaki/root` (`90-docs/adr/`).
