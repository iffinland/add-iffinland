# Qortal Community — Roles Directory

Welcome! This repository is a community‑run initiative under the **Qortal Community** GitHub organization. Its purpose is to help anyone interested in contributing to the Qortal platform quickly see where help is needed and where they might fit into the development process — **including non‑coders**. Translators, testers, documentation writers, issue triage helpers, reviewers, designers, security reviewers, and more are all welcome.

This list is intentionally simple: contributors **self‑assign** roles by adding themselves to the tables below via pull request. Only your GitHub handle is required; all other fields are optional.

> **Privacy note:** Please do not include personal emails, phone numbers, or sensitive details. Your GitHub handle is sufficient. Use a UTC offset (e.g., `UTC-5`) rather than a city/country. If you’re unsure of your UTC offset, use the [UTC time zone converter](https://www.utctime.net/utc-time-zone-converter).

---

## 1) What this is & how it works

- **Community initiative.** This list is by and for the community to coordinate contributions and make it easy to discover needs across code and non‑code work.
- **Self‑assigned roles.** Add yourself under one or more roles that match your interests and availability.
- **Light governance.** For now, a single maintainer can merge valid PRs that add rows to these tables (see rules below). Maintainers are placeholders until named.
- **Inclusive by design.** You do **not** need to be a developer to help. Translators, testers, triage, docs, UX, outreach — all are crucial to Qortal’s success.

_Repo maintainers (merge reviewers): **Role pending**_

---

## 2) Suggested Roles (additive, not limiting)

Below are **suggested** categories to get started. You are **not** limited to these. If a role you need is missing, see **“Add a brand‑new role”** in the instructions section.

> Formatting rules for all tables:
> - Columns: `| GitHub | Languages | Timezone | Notes |` (only **GitHub** is required)
> - Sort rows **alphabetically by GitHub handle** (e.g., `@alice`, `@bob`, `@carol`)
> - Use short language tags (e.g., `en`, `es`, `de`) and UTC offsets (e.g., `UTC-5`)
> - Placeholders use en‑dashes `—` for empty cells

### Developers (Platform or Q-Apps)
_Builds/maintains Qortal Core, Qortal Hub, or Q-Apps; ships features end-to-end across frontend/backend and tooling._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| [QuickMythril](https://github.com/QuickMythril) | en | UTC-5 | Core / Hub / Q-Apps |

### Translators
_People who translate UI, docs, and announcements. Please list your languages._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Issue Triage
_Find feedback from forums/social/Discord/etc. and create actionable GitHub issues in the right repo._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Reviewers (Code/Docs)
_Review pull requests for correctness, clarity, and alignment with project style/architecture._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Documentation
_Write or improve READMEs, guides, FAQs, API/docs, and contributor onboarding material._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### QA / Testing
_Test features, write repro steps, suggest test cases, and help maintain test matrices._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Security Review
_Perform threat‑modeling, code review for security, and responsible disclosure coordination._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### DevOps / Infra
_CI/CD, build pipelines, automation, infra scripts, and release packaging._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### UI/UX & Design
_User research, wireframes, mockups, UX writing, accessibility reviews._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Community & Outreach
_Coordinate announcements, write updates, manage social posts, organize community calls._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

### Release Coordination
_Changelogs, release notes, cross‑repo coordination, and smoke‑testing for releases._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |

---

## 3) How to add yourself (self‑assign a role)

You can use the GitHub web UI — no CLI required. The process takes a minute or two.

### A. Fork this repository
1. Click **Fork** (top‑right) to create your copy.

### B. Create a branch
- Name your branch `add-(name)` using your **GitHub handle** (recommended), e.g. `add-alice`.

### C. Edit `README.md`
1. Open your fork’s `README.md`.
2. Add a new row under the table for the role(s) you want. Keep tables **alphabetized by GitHub handle**.
3. Only the first column is required. Optional columns help coordination.

**Row format example:**

```
| [alice](https://github.com/alice) | es, en | UTC+1 | Available on weekends |
```

> If you don’t know your UTC offset, use the [UTC time zone converter](https://www.utctime.net/utc-time-zone-converter).

### D. Commit and open a Pull Request (PR)
1. Commit your change to your `add-(name)` branch.
2. Open a PR back to this repo with a title like: **“Add @alice to Translators”**.
3. Keep the PR minimal: **only** change `README.md` and **only** add your own row(s).

### E. Review & merge
- A maintainer will do a quick sanity check and merge (1 approver required).  
- If changes are requested, push updates to the **same branch**.  
- If there’s a merge conflict, re‑open your fork’s `README.md` and re‑apply your row in the correct alphabetical spot.

### F. Add a brand‑new role (if needed)
If your role isn’t listed, please add a new section using this template and then add your row:

```
### <Your Role Name>
_One‑line description._

| GitHub | Languages | Timezone | Notes |
|---|---|---|---|
| Role pending | — | — | — |
```

---

## Ground rules (keep it simple)

- **Scope:** PRs should only edit `README.md` to add *your own* entry (or add a new role section + your entry).
- **Ordering:** Keep entries alphabetized by GitHub handle within each table.
- **Links:** Avoid tracking links. No personal emails/phones or sensitive info.
- **Respect:** Be kind. No harassment or spam. (A full Code of Conduct may be adopted later.)

---

## License

**CC0 1.0 Universal (Public Domain Dedication).**  
To the extent possible under law, contributors have dedicated this work to the public domain. By contributing to this list, you agree to release your contribution under CC0.  
See: <https://creativecommons.org/publicdomain/zero/1.0/>

---

_Happy contributing!_
