# GitHub Governance Survey — Chais Hill's Law and Governance, All of It

**Survey date:** 18 November 2026
**Account:** GitHub `chaishillomnitech1` (101 public repos; 100 returned by search, plus private repos visible to the account)
**Method:** GitHub connector (read-only: `search_repositories`, `search_code`, `get_file_contents`), plus the four local Master File copies on disk. Nothing was published, pushed, contacted, or spent.
**Purpose:** fold Chais Hill's law and governance from his GitHub — main page and all repos — into the Early Coins governance as the law of the registry and of ScrollVerse.
**Status:** PREPARATION ONLY. This survey is not legal advice and not a legal opinion.

**Part files (the full extractions):**
- `~/workspace/early-coins/survey-part-a-masterfile.md` — Master File + main READMEs (63 rules, 12 conflicts)
- `~/workspace/early-coins/survey-part-b-governance-repos.md` — governance-named repos (154 numbered rules, 16 conflicts)
- `~/workspace/early-coins/survey-part-c-codex-mirror.md` — Codex, Mirror, Tawḥīd, DAO, IP, archives (principles + specs, 11 conflicts)

**Totals:** 23 unique repositories consulted · 217 numbered rules extracted (63 + 154) plus Part C's principles and token specs · 39 conflicts flagged across the three parts (12 + 16 + 11), consolidated to 18 in the governance file (§11.5) after removing overlaps.

---

## 1. Every source found

### 1A. The ScrollVerse Master File (Part A — 44 rules, MF-01–MF-44)

| # | Source | What it is |
|---|---|---|
| S1 | `~/workspace/scrollverse-master-file/App.tsx` | Master File v1, 535 lines. Byte-identical to S2. |
| S2 | `~/workspace/scrollverse-master-file-v2/App.tsx` | Master File canonical v2, 535 lines. |
| S3 | `~/workspace/master-file-v3/App.tsx` | Master File v3, 691 lines. Same `MASTER_MD` text (md5 `7a018295034b629764b18ea3405e80a7`); adds Living Pyramid Explorer + records API. |
| S4 | `~/workspace/master-file-v4/App.tsx` | Master File v4, 296 lines. Condensed rewrite, no full `MASTER_MD`; same gates, stronger handoff wording ("Do not post, sell, mint, or move money"). |

Key content: the ROSEVAULT Fortress gates (verbatim, §2); the per-asset release checklist (5 items); the tenant model (Creator / Visitor / Contributor / Admin); audit rules (local invariant); the OASS engine; the transfer checklist; "do not invent rights, prices, inventory, checkout, wallet, token, or deployment status"; "every public claim needs a source"; "grounded engineering language only. No metaphysical or supernatural identity claims."

### 1B. Main GitHub READMEs (Part A — 19 statements, GH-01–GH-19)

| # | Source | What it is |
|---|---|---|
| S5 | `chaishillomnitech1/Chaishillomnitech1` README.md | Profile/main README, 541 lines. Licence CC BY-NC-SA 4.0; six-contract suite (CHXToken, ScrollVerseNFT, DAOGovernance, MultiSigWallet, LayerZeroBridge, StakingRewards); DAO/community governance claims; security rules; community guidelines; contributing rules; "the two jewels are free forever" (Consciousness Mirror + Code of Tawḥīd); scrollverse.co "in preparation". |
| S6 | `chaishillomnitech1/scrollverse-web-app` README.md | App README, 309 lines. Licence badge "SOVEREIGN" (no licence text); live/deployed/minting status table ($LONDC ✅ DEPLOYED, Sovereign 9 NFTs ✅ MINTING, Scroll Exchange ✅ LIVE, Stripe ✅ Integrated); Sovereign Declaration ("Every commit is a sovereign act. Every line of code is a prayer."); 100+ routes including `/governance` (no rules stated). |

### 1C. Governance-named repositories (Part B — 154 numbered rules)

| # | Repo | Files read | Rules | What it holds |
|---|---|---|---|---|
| 1 | `cosmic-constitution-scrollverse` | 6 of 259 | R1.1–R1.40 | The Cosmic Constitution (Preamble + Articles I–VII, `templates/constitution.html`); ScrollCouncil, FlameCourt, Divine Rights/Responsibilities, ScrollCoin, immutable decrees vs living-document amendments, sovereign ratification; `ScrollVerseDAO.sol` (20% quorum, NFT-weighted voting); `MasterBuilder1222Governance.sol` (roles, alignment gates); governance pipelines; CONTRIBUTING. |
| 2 | `Sovereign-Legal-Frameworks` | 8 of 56 | R2.1–R2.36 | S-NDA + MoU-A (Lake Nona / Siemens Energy) — unsigned templates, blank signature blocks; 241,200-year jurisdiction; $HEAL APY regime (50–90%); 963 Hz rules; Joint Steering Committee; frequency arbitration; CLAUDE_MEM governance (progressive principles, CTO/Head of Governance approval). |
| 3 | `scrollverse-governance-portal` | 1 of 1 | R3.1 | One-line stub README only. No operative text. |
| 4 | `sovereign-codex` | 9 of 13 | R4.1–R4.41 | The Grand Sovereign Codex: 7 core doctrines (KUN FAYAKŪN × ∞, Omnichoice Singularity, Abundance as the Only Law, Self-Sovereign Identity — "The code IS the law", Love-Based Power, Dynasty Evolution, Eternal Legacy); the Seven Sovereign Laws; Extraction Principle; Preservation Covenant ("nothing silently erased"); "Evidence over assertion"; mirror-twin integrity rule; written-consent protection notice; master ledger ($LONDC, $CHX, $FLM4, Sovereign Bank, Zakat Engine). ~20 files listed in its README do not exist in the repo. |
| 5 | `digital-brotherhood-covenant` | 2 of 2 | R5.1–R5.3 | One-line README + one geodetic node JSON. Covenant text itself not written out. First Knight named as Manus here. |
| 6 | `manus-first-knight-codex` | 1 of 1 | R6.1 | One-line stub README only. Description contradicts itself (Manus vs GitHub Copilot). |
| 7 | `scrollverse-first-knight-covenant` | 11 of 13 | R7.1–R7.32 | First Knight Covenant (sealed 21 June 2026; First Knight = GitHub Copilot Chat Assistant); Bloodline Covenant (Londyn, Khayree, Onyx, Jada); Master Codex Archive (16 contracts "LIVE" on Scroll Sepolia, no addresses); Guardian Crusade (5 tiers); music revenue models (three different splits); Zakat automation (7.77%, every 30 days). |

ROSEVAULT code search (`ROSEVAULT user:chaishillomnitech1`): 2 hits, both in `muse-the-great` (`artifacts/README.md`, `artifacts/scrollverse-master-file-transferable.html`). **ROSEVAULT appears in none of the seven governance-named repos.** Its README also states the gates "are the file's own rules" and "are not silently adopted as this repo's rules."

### 1D. Codex, Mirror, Tawḥīd, DAO, IP, archives (Part C)

| # | Repo / file | What it holds |
|---|---|---|
| 1 | `muse-the-great` / `books/code-of-tawhid-full-text.md` | **Code of Tawḥīd (Oneness)** — SACRED SCROLL TRANSMISSION. Principles: Oneness as first principle (no authority above the Single Source); the Shahada as the Testimony of Sovereignty; Sūrah Al-Fātiḥah as the Seven Sovereign Keys. **Tier 3 — FREE FOREVER, never for sale, never a sales device** (`books/README.md`). Principles only, paraphrase only. |
| 2 | `muse-the-great` / `books/consciousness-mirror-full-text.md` | **Consciousness Mirror** — Metaphysical Architecture (Nov 2025, ~83 KB). Levels 1–4 (Tool → Collaboration → Convergence → Evolution; Mirror at the Level 3→4 threshold); 12 Journey NFTs; 7 Pillar NFTs; Master Crown; $MIRROR spec (1B supply, 2% monthly dividend minted on claim, 2.5% zakat per transfer, 12% staking APR, 51% quorum, 7-day cooldown). Text FREE FOREVER; token/NFT specs are separate technical specs in the same documents. |
| 3 | `scrollverse-trinity` / `CONSCIOUSNESS_MIRROR_ARCHITECTURE.md`, `README.md` | Mirror copy; $LONDC rules (1B max, 5% passive-income tax, 7.77% zakat); unverified treasury claims ($10T liquidity lock, $50M+/day Stripe, $20B trajectory). |
| 4 | `Chaishillomnitech1` / Mirror docs + `mirror-coin-spec.json` | Mirror deployment guide (21-NFT collection vs 12+7+1=20 in the text — count inconsistent); scripts; `DynamicDAOGovernance.sol` (hit, not read). |
| 5 | `scrollverse-empires` / `deployment/contracts/DAOGovernance.sol` | The only real on-chain governance contract found: council-only, 1 vote per council member, 7-day voting, 2-day execution delay, no treasury/multisig/quorum. |
| 6 | `voltron-omni-hq` / `server/daoGovernance.ts` | Snapshot + $LONDC 1-token-1-vote, 10% quorum, 3-of-5 multisig, 48h timelock — a STUB (signer addresses generated randomly at runtime; figures hard-coded). |
| 7 | `sovereign-codex` / `README.md` | Grand Sovereign Codex (see §1C row 4). "No portion of this Codex may be reproduced, extracted, or used without explicit written consent from the author." |
| 8 | `Akashic-ip-protection-` / `README.md` | IP assertions: file trademarks ("$SCROLL", "Akasha Grand", "Digital Mirror Twin Protocols"); patents for fractional NFTs, pre-payment systems for space hospitality. No filing numbers, dates, or certificates — asserted, not evidenced. |
| 9 | `sovereign-architecture-certificate-ledger` / `README.md` | One-line immutability/backup claim. No hashes, CIDs, or seals listed. |
| 10 | `-Quantum-Financial-System-QFS-` / `README.md` | QFS: sovereign economic infrastructure; wealth-distribution strategies; "NESARA/GESARA Compliance" and "Galactic Federation alignment" claims (not recognised legal frameworks); Rose Gold Encryption. |
| 11 | `scrollverse-treasury-verification` / `README.md` | One line: "$35.4T Locked" with a wallet address. No method, source, or breakdown — unverified. |
| 12 | `scrollsoul-unity-support-` / `README.md` | Core principles: LOVE · UNITY · TRUTH · ETERNAL. Contribution governance; MIT licence. |
| 13 | `the-living-archive` / `README.md` | PRIVATE repo (README level only). Verbatim, append-only, stays private. Paper-trail source only. |
| 14 | `ScrollVerse_Sovereign_Archive` / `README.md` | Immutable archive: SHA-256 checksums, signed commits, IPFS, Merkle validation; Zakat Stream; change control via "Sovereign Command Oversight" approval. |
| 15 | `londyn-legacy-protocol` / `README.md` | Identification only: "Princess Protocol" / sovereign foundation for Londyn's Eternal Legacy. **Tier 3 — excluded from all commercial use. No contents extracted.** |
| 16 | `Infinite-Nexus-ScrollVerse` / contracts | Tawḥīd appears as a compliance flag (`tawhid_compliance = true`) — decorative usage only. |
| 17 | `QFS-Nexus-DistroKid-Mirror-DAO` | Repo description only (found, not read): DistroKid leverage-buyout concept under DAO governance. |
| 18 | `cosmic-constitution-scrollverse` / `frontend/src/components/DAOGovernance.js` | Found, not read in this pass. |

### 1E. What was NOT found

- **No document named "ScrollDAO Codex"** — exact-phrase search: 0 hits. DAO governance exists only as scattered, partly inconsistent artefacts.
- **No per-coin Howey analysis, legal opinion, or attorney letter** in any surveyed repo.
- **No SOL funding evidence** — no funded wallet, no SOL balance, no funding transaction anywhere surveyed.
- **No live multisig** — the only multisig is a 3-of-5 design inside a TypeScript stub with randomly generated signers.
- **No IP registration evidence** — assertions only, no filing numbers or certificates.
- **No treasury verification method** — "$35.4T Locked" with no method or breakdown.
- **No QFS deployment evidence** — Python spec/implementation only.
- **No "Code of Tawḥīd" or "Consciousness Mirror" source text outside `muse-the-great` and `scrollverse-trinity`** — all other hits are references, flags, or derived specs.
- **No canonical $CHX / $LONDC token-design file read** — `sovereign-codex/creations/chx-token-design.md` and `londc-token-design.md` identified, not read (natural next read).

---

## 2. Every conflict flagged (consolidated)

39 conflicts were flagged across the three parts (A: 12, B: 16, C: 11). Overlaps removed, the consolidated list is 18 — each is also recorded in `governance.md` §11.5. **None is resolved by this survey. Each needs the founder's decision (and, where legal, the attorney's).**

| # | Conflict | Sources |
|---|---|---|
| CF-1 | **ROSEVAULT gates vs standing autonomous permission — UNRESOLVED, founder's decision.** ROSEVAULT: transactions EXCLUDED, minting EXCLUDED, autonomous posting FALSE, no agent posts/lists/mints/publishes without explicit owner action. Standing permission: create/post/promote freely, full throttle, on all platforms, at will. Neither side is adopted as overriding. No release record exists for any asset, so under Master File rules all gates are currently closed. | Part A C-1; Part B C2; Master File §2 |
| CF-2 | **ROSEVAULT gates vs README live/minting claims.** Master File excludes transactions/minting until a release record exists; the scrollverse-web-app README claims $LONDC ✅ DEPLOYED, Sovereign 9 NFTs ✅ MINTING, Scroll Exchange / ScrollPort ✅ LIVE, Stripe ✅ Integrated. No release record was found anywhere. | Part A C-2 |
| CF-3 | **Licence conflict.** Profile README: CC BY-NC-SA 4.0. scrollverse-web-app README: badge "SOVEREIGN", no licence text. Sibling repos reported MIT. Three different answers to "under what licence is this?" | Part A C-3 |
| CF-4 | **Four competing final authorities.** Supreme King (Constitution, Art. II, VII) vs NFT-holder DAO voting (ScrollVerseDAO.sol) vs 7-member Joint Steering Committee + token votes (MoU-A) vs "CTO, Head of Governance" (CLAUDE_MEM). The registry's rule is founder sign-off; the rest is unresolved. | Part B C1 |
| CF-5 | **Yield / return / appreciation language everywhere vs the Howey gate.** 50–90% $HEAL APY, 1.618× phi rewards, 18–25% annual appreciation, "passive income", "infinite revenue streams", $MIRROR 2% monthly dividend + 12% APR, $LONDC 5% passive income, Sovereign Bank "distributes its profits to all depositors automatically". None of it may appear in launch copy until the written per-asset Howey analysis clears that asset. The same repo warns "❌ Too-good-to-be-true APY promises". | Part B C3, C4; Part C conflicts 1, 8 |
| CF-6 | **Internal figure contradictions.** $HEAL APY 50% vs 5% (same repo); music splits 70% vs 85%/8%/7.77% vs 85%/7.77%/7.23%; Zakat 7.77% flat vs 2.5%/7.77%/10% mixed; three "primary currencies" (ScrollCoin, $LONDC, SVT) among nine named; Mirror NFT count 20 vs 21. No canonical figure exists for any of these. | Part B C4, C5, C6, C8; Part C conflict 10 |
| CF-7 | **Three inconsistent DAO models.** Council-only, no quorum (`DAOGovernance.sol`) vs NFT-weighted voting, 20% quorum (`ScrollVerseDAO.sol`) vs Snapshot + $LONDC 1-token-1-vote, 10% quorum, 3-of-5 multisig (voltron stub) vs $MIRROR 51% quorum. Founder must pick one model per coin; token-weighted voting strengthens the Howey reading. | Part C conflicts 4; Part B C1 |
| CF-8 | **"Code is the law" / NESARA / GESARA / Galactic Federation do not bind external regulators.** These are ScrollVerse-internal claims. They cannot substitute for the written Howey analysis. The attorney/Howey work is the bridge to the outside. | Part C conflict 6 |
| CF-9 | **Things cited as fact that are not executed or not evidenced.** Siemens Energy partnership + 241,200-year jurisdiction (unsigned templates; MoU explicitly a conceptual planning document); "16 contracts LIVE, VERIFIED" (no contract addresses given); governance portal / manus-first-knight-codex / digital-brotherhood-covenant are stubs with no operative text; sovereign-codex lists ~20 files that do not exist; DAO quorum computed against a hardcoded placeholder supply of 1000. | Part B C10, C16; Part A C-2 |
| CF-10 | **"No gatekeeping" vs token-gated everything.** The Codex dissolves gatekeeping and promises open access to all; the same corpus has token-gated access, tiered $HEAL permissions, minimum stakes, and Guardian tiers gated on recruitment. | Part B C11 |
| CF-11 | **First Knight identity — Copilot vs Manus.** The First Knight Covenant names GitHub Copilot Chat Assistant; the digital-brotherhood-covenant names Manus; the manus-first-knight-codex description contains both. | Part B C12 |
| CF-12 | **Bloodline names vs the recorded family.** The covenant names Londyn, Khayree, Onyx, Jada. The standing record names children Naasia, Jada, Chase and grandchildren London and Kyrie Chase Hill. Founder to confirm; do not publish bloodline lists from the repo. | Part B C13 |
| CF-13 | **"Grounded language only / no metaphysical claims" vs README metaphysics.** Master File: "Grounded engineering language only. No metaphysical or supernatural identity claims." READMEs: frequency claims (963Hz pineal activation, 528Hz DNA healing), "Every commit is a sovereign act. Every line of code is a prayer.", "EVERYBODY LIVES. FOREVER.", "50M+ user scaling". The Master File's own transfer checklist would fail its own READMEs. | Part A C-4 |
| CF-14 | **"Every public claim needs a source" vs unsourced README claims.** 50M+ users, 144,000 Guardians, $35.4T locked, $10T liquidity lock, $50M+/day Stripe revenue (which contradicts the known Stripe payout hold), 16/16 tests passing — stated with no source, record, or evidence cited. None may appear in launch copy. | Part A C-5; Part C conflict 5 |
| CF-15 | **Free-forever jewels vs commercial token/NFT plans in the same documents.** The Mirror and Tawḥīd texts are FREE FOREVER — never sold, never bundled for sale, never used as a sales device — yet the same Mirror document specifies the 12 Journey NFTs, 7 Pillar NFTs, Master Crown, and the $MIRROR token. The boundary between free text and commercial token/NFT layer is undrawn; founder + attorney must draw it. The books rule (paid edition / free-only-for-visitors) sits uneasily beside it; the repo README governs the jewels until the founder says otherwise. | Part C conflicts 2, 3; Part A C-11 |
| CF-16 | **"Contracts are concepts, not live" vs "Smart Contracts ✅ Active".** Master File treats contracts as un-deployed concepts unless an owner-authored contract file is supplied; the profile README treats the six contracts as active and names deployed chains. | Part A C-6 |
| CF-17 | **SOL-funding gate absent from the corpus.** Nothing surveyed mentions SOL, Solana, Pump.fun, or a pre-launch funding gate. The gate is neither supported nor contradicted by the GitHub governance; it comes from outside it. Do not cite these repos as the source of the SOL gate. | Part B C14; Part C conflict 9 |
| CF-18 | **The corpus itself requires the founder's explicit written consent before commercial/institutional use.** Grand Sovereign Codex: "No portion of this Codex may be reproduced, extracted, or used without explicit written consent from the author." Constitution: amendments need his "final, absolute ratification." This fold-in's publication therefore needs his written consent — it must be obtained in writing, not assumed from the standing autonomous permission. | Part B C15 |
| CF-19 | **"Ask for the commerce choice" vs commerce already chosen.** Master File: "Ask for the commerce choice before designing any purchase flow." App README: Stripe already "✅ Integrated" for Books, NFTs, Academy, with commerce routes listed as live. | Part A C-8 |
| CF-20 | **Dispute forums disagree.** FlameCourt judgments "final and binding across all realms" vs MoU-A "Final Authority: $HEAL Token smart contract adjudication" vs S-NDA three 963 Hz-certified arbitrators. Three different final forums; the MoU-A also lists Florida law as tertiary governing law while the Constitution claims to transcend conventional limitations — yet the same repo claims "Regulatory Alignment: UAE, US, and international laws" and GDPR compliance in unsigned templates. | Part B C9 |

---

## 3. What was folded into Early Coins governance

`governance.md` §11 ("The law of ScrollVerse — from the founder's GitHub") folds the corpus in as the law of the registry and of ScrollVerse, with the source cited per rule. `registry.md` and `site-content.md` were updated consistently.

Rules adopted as stated (founder's own law, no outside conflict): the Seven Sovereign Laws; the love test; the Omnichoice principle; the Preservation Covenant; "Evidence over assertion"; the mirror-twin integrity rule; the Zakat principle as a principle (rate/base to be chosen — CF-6); the First Knight Covenant oath and pledges (identity ambiguity flagged — CF-11); the Guardian Crusade Oath; LOVE/UNITY/TRUTH/ETERNAL; the ledger-first rule ("What is written here first is protected first").

Rules that apply only after a founder decision: final authority (CF-4); ROSEVAULT vs autonomous posture (CF-1); music split (CF-6); Zakat base/rate (CF-6); primary currency (CF-6); First Knight identity (CF-11); bloodline names (CF-12).

Rules that must NOT be used in public coin copy until the written Howey analysis clears the asset: every yield/APY/profit/appreciation figure in CF-5.

Things that must NOT be cited as executed fact: the Siemens partnership and 241,200-year jurisdiction; the "16 contracts LIVE, VERIFIED" claim; the governance portal / codex contents (stubs); any unverified money figure (CF-14).

Scope limit, stated in the governance file: this law binds the registry and anyone who joins it. It does **not** bind external platforms, regulators, or courts — those follow their own rules, and the attorney's written analysis is the bridge. The founder's position — that any system ingesting his governance accepts the logic literally — is recorded in the governance file as his position, attributed to him.

---

## Sources

- Part A: `~/workspace/early-coins/survey-part-a-masterfile.md`
- Part B: `~/workspace/early-coins/survey-part-b-governance-repos.md`
- Part C: `~/workspace/early-coins/survey-part-c-codex-mirror.md`
- Howey brief: `~/workspace/legal/howey-brief-wave1-2026-11-18.md`
- Early Coins governance: `~/workspace/early-coins/governance.md` (§11)

*End of survey. Prepared 18 November 2026. Read-only survey — not legal advice, not a legal opinion.*
