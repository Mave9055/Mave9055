# Repository Consolidation Plan

This document defines the clean public structure for the Mave9055 / Capitol Contracts LLC GitHub account.

The goal is to reduce scattered project history into a small set of serious, understandable repositories that support the public mission:

- Capitol Contracts LLC business credibility
- WRH non-clinical psychoeducational curriculum
- pilot deployment materials
- public education articles
- memoir and book production
- protected archive/research work kept separate from public-facing assets

## Final Public Repo Map

These repositories should remain visible, polished, and clearly described.

| Repository | Role | Public Purpose |
|---|---|---|
| `capitol-contracts` | Company hub | Business identity, services, capability language, procurement-safe documentation |
| `wrh-master-curriculum` | Curriculum source of truth | Full WRH framework, session architecture, facilitator structure, glossary, staff tools |
| `WRH-Pilot-Deployment-Package` | Field deployment package | Practical pilot version for organizations, peer programs, recovery/reentry settings, and partners |
| `top-10-core` | Short public entry point | Ten core concepts and shorter introductory program |
| `ebook-manuscript` | Public article/manuscript site | Counter-narrative essays, excerpts, reader-facing education |
| `from-storm-to-fire-book-production` | Book production workflow | Markdown, HTML/CSS, PDF/ebook production, covers, exports |
| `trauma-archive` | Archive/platform, if polished | Documentary archive or structured public knowledge base |
| `Mave9055` | Profile hub | Public GitHub landing page and repository map |

## Repositories to Merge Into `wrh-master-curriculum`

Move any useful content from these repositories into `wrh-master-curriculum`, then archive or delete the old shells after verification:

- `trauma-recovery-curriculum`
- `cptsd-education-portal`
- `cptsd-presentation-web`
- `betalectures`
- `What-Really-Happened-Manual`
- `CPTSD-Straight-Facts`
- `lesson-collection-site`
- `wrh-portal`
- useful material from `wrh-master-platform`

Suggested destination folders:

```text
wrh-master-curriculum/
  content/
    sessions/
    lectures/
    facilitator-guides/
    participant-materials/
    staff-tools/
    glossary/
  docs/
  public-site/
  archive-imports/
```

## Repositories to Merge Into Book Production

Move production-relevant material into `from-storm-to-fire-book-production`:

- final manuscript source
- print/PDF build files
- cover files
- export files
- layout CSS/HTML
- Payhip-ready versions

Likely sources:

- `from-the-storm-to-the-fire`
- `new-ebook-manuscript`
- `What-Really-Happened-The-True-Story`
- selected production pieces from `ebook-manuscript`

Keep `ebook-manuscript` only if it remains the public staging/article site.

## Repositories to Merge Into `capitol-contracts`

Only business-facing materials should move here:

- capability statement
- leadership/control language
- service descriptions
- NAICS/service framing
- procurement-safe scope boundaries
- pilot offering summaries
- contact/partner information

Likely sources:

- useful pieces from `nervous-system-marketing`
- selected buyer-facing summaries from `WRH-Pilot-Deployment-Package`
- selected company/platform language from `wrh-master-platform`

Do not dump raw curriculum, personal narrative, or private research into the company repo.

## Repositories to Make Private, Rename, or Keep Separate

These should not be featured in the public business/curriculum profile without review:

- `melinda-walker-dossier`
- `ashton-investigation-report`
- `OSINT`
- `horner-archive`
- `fort-wolters-lighter-archive`
- `texas-holdem-sweepstakes`

Reason: public repo names involving dossiers, investigations, OSINT, or gambling-adjacent projects can distract from the credibility of Capitol Contracts and WRH.

Preferred action:

1. Make private if the material is personal, sensitive, or unfinished.
2. Rename neutrally if it must remain public.
3. Move verified research material into a private `private-research-archive`.
4. Keep it completely separate from business/curriculum repos.

## Repositories to Archive After Checking for Unique Files

These appear to be old builds, duplicates, or experiments:

- `new-ebook-manuscript`
- `What-Really-Happened-The-True-Story`
- `What-Really-Happened-Manual`
- `what-really-happened-redesign`
- `what-really-happened-site`
- `cptsd-presentation-web`
- `cptsd-education-portal`
- `trauma-recovery-curriculum`
- `wrh-portal`
- `betalectures`
- `lesson-collection-site`
- `ideal-octo-disco`
- `mix`
- `termux-app`

Archive only after confirming that useful files have been moved into the correct destination repo.

## Repositories to Keep Separate as Side Brands or Experiments

These should not be mixed into WRH or Capitol Contracts unless there is a deliberate business reason:

- `blackline-flameworks`
- `torch-finished-furniture`
- `electronics_treasure_hunt`
- `melody-maker`
- `26laws`
- `texas-holdem-sweepstakes`

## Order of Operations

1. Protect credibility first: make sensitive/personal/risky repos private or rename them neutrally.
2. Keep the GitHub profile README focused on the official repo map.
3. Build `capitol-contracts` into the clean business hub.
4. Merge all curriculum fragments into `wrh-master-curriculum`.
5. Keep `WRH-Pilot-Deployment-Package` separate as the buyer/implementation package.
6. Merge book production files into `from-storm-to-fire-book-production`.
7. Keep `ebook-manuscript` as the public article/manuscript preview site.
8. Archive duplicate repos only after content has been checked.

## Rule

Do not delete repos until their useful files have been identified, moved, or intentionally rejected.

The purpose of this consolidation is not to erase the work. The purpose is to make the work understandable.