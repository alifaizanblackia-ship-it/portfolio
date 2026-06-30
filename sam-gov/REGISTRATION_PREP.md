# SAM.gov Entity Registration — Prep Packet

> **Entity:** ElectroCom IT · **Goal:** Full registration (eligible to bid on US federal awards)
> **Owner:** Faizan (BD) · **Reviewer:** Arslan / Zulfiqar
> Last updated: 2026-06-30

This packet pre-fills everything ElectroCom already knows, flags the data we still need,
recommends NAICS codes, and gives the exact step-by-step for the live SAM.gov flow.
SAM.gov requires a personal **Login.gov** sign-in and on-site entry of sensitive fields
(EIN, bank/EFT) — those can't be filled in advance, only prepared.

---

## STEP 0 — Check if we're already registered (DO THIS FIRST)

Our internal notes say "SAM.gov registered," but that's unconfirmed. Re-registering a
duplicate entity causes a validation failure, so verify first.

1. Go to **sam.gov → Search** (no login needed).
2. Select the **Entity Information** domain.
3. Search the legal business name **"ElectroCom"** and the Celina, TX address.
4. Outcome:
   - **Found + Active** → we're registered. Switch to **renew/update** path (Entity Workspace → Renew). Stop here, tell the team.
   - **Found + Inactive/Expired** → registration lapsed. Renew it (don't make a new one).
   - **Not found** → proceed with new registration below.

> Also worth checking: does anyone on the team already hold the **Login.gov** account and
> **Entity Administrator** role? If a prior employee registered it, we may need to request
> the admin role rather than start fresh.

---

## STEP 1 — Data we ALREADY have ✅

| Field | Value |
|---|---|
| Physical address | 2750 S Preston Rd Ste 1167, Celina, TX 75009, USA |
| Website | electrocomit.com |
| Employee count | 11+ |
| Founded (operating history) | 1998 (telecom roots → full IT services) |
| Primary business | IT solutions / software / AI-ML engineering |

---

## STEP 2 — Data we NEED before starting ⚠️ (fill these in)

These come from the company's US formation documents and IRS records. **The legal name and
address must match the IRS EIN letter EXACTLY** or registration fails validation.

| Field | Why it's needed | Value (FILL IN) |
|---|---|---|
| **Exact legal business name** | Must match IRS/state filing char-for-char (e.g. "Electrocom IT LLC" vs "ElectroCom IT Inc") | __________ |
| **Entity structure** | LLC / C-Corp / S-Corp / etc. | __________ |
| **State of incorporation** | Likely TX | __________ |
| **US business start date** | Date the US entity was formed (NOT 1998 — that's the telecom origin) | __________ |
| **EIN / TIN** (9-digit) | IRS taxpayer ID — must match IRS name. *Sensitive — enter on-site only.* | __________ |
| **Name exactly as on IRS records** | For the IRS TIN match step | __________ |
| **Bank routing + account #** | For EFT (how the govt pays you). *Sensitive — enter on-site only.* | __________ |
| **Prior-year annual revenue** | For small-business size determination | __________ |
| **DBA (if any)** | "Doing business as" name, if different from legal | __________ |

---

## STEP 3 — Points of Contact (POCs)

SAM.gov requires named POCs. Recommended mapping (confirm with team):

| Role | Suggested person | Email |
|---|---|---|
| Entity Administrator | Faizan or Arslan (whoever owns the Login.gov account) | __________ |
| Electronic Business POC | Arslan Noor (CTO) | arslan@electrocomit.com |
| Government Business POC | Zulfiqar Saeed (CEO) | __________ |
| Past Performance POC | Arslan Noor | arslan@electrocomit.com |

> Consider routing the govt-business POC to **partnerships@electrocomit.com** once that alias
> is live, so federal correspondence is tracked separately from commercial BD.

---

## STEP 4 — Recommended NAICS codes

NAICS = the industry classifications that determine which solicitations match us and whether
we qualify as a small business. **Pick ONE primary + several secondary.** For a software/AI/IT
shop with 11 staff, we comfortably qualify as a **small business** under all of these (their
size standards run $19M–$34M in revenue — well above us), which unlocks small-business set-asides.

**Primary (recommended):**
- **541511 — Custom Computer Programming Services** → web/full-stack/SaaS dev. Best fit for our core. *(Size std: $34M)*

**Secondary:**
- **541512 — Computer Systems Design Services** → architecture, systems integration, AI systems
- **541519 — Other Computer Related Services** → catch-all incl. staff augmentation/IT services
- **518210 — Computing Infrastructure Providers, Data Processing, Web Hosting** → managed IT, cloud, DevOps
- **541611 — Administrative & General Management Consulting** → strategic IT consulting / digital transformation
- **541715 — R&D in Physical, Engineering & Life Sciences** → optional, for AI/ML research framing
- **561320 — Temporary Help Services** → optional, if pitching staff augmentation to govt teams

> Map to our 5 service pillars: Web Dev → 541511 · AI/ML → 541512/541715 · Managed IT → 518210 ·
> Consulting → 541611 · Staff Aug → 541519/561320.

---

## STEP 5 — Reps & Certifications (heads-up)

Full registration ends with the FAR/DFARS reps & certs — a long yes/no questionnaire
(business types, small-business status, ownership, no debarments, etc.). Nothing to prepare in
advance, but budget ~30–45 min. Answer honestly; small-business and any
minority/disadvantaged-owned status here drive set-aside eligibility.

---

## STEP 6 — The live flow (order of operations)

1. **Create/sign in to Login.gov** (personal account for the person registering).
2. sam.gov → **Get Started → Register Entity** → choose **"Bid on contracts / apply for awards."**
3. Enter **entity details** (legal name, address, start date, structure) → SAM validates against public records → assigns a **Unique Entity ID (UEI)**.
4. **IRS TIN match** (EIN + IRS name) — can take 1–2 business days.
5. **CAGE code** assigned automatically for US entities.
6. Enter **banking/EFT** details.
7. Add **POCs** (Step 3).
8. Complete **Reps & Certs** (Step 5).
9. Submit → **up to 10 business days to go Active.**

---

## STEP 7 — Free help available

- **APEX Accelerators** (formerly PTACs) — free, government-funded help completing SAM.gov registration. Find the local TX office; worth using for the first registration.
- **Federal Service Desk** — fsd.gov, live chat/phone Mon–Fri 8am–8pm ET, for technical issues.

---

## Outstanding actions
- [ ] Run Step 0 entity-status check
- [ ] Fill all ⚠️ fields in Step 2 (from US formation docs + IRS letter)
- [ ] Confirm POC mapping (Step 3)
- [ ] Confirm primary + secondary NAICS (Step 4)
- [ ] Decide who holds the Login.gov / Entity Admin account
