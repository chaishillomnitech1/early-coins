# Early Coins — Registration System

**Issuer:** ScrollVerse LLC — New Jersey single-member LLC, formed 12 May 2026. Sole member: Chais Hill, artist "Chais the great", founder of ScrollVerse LLC.
**System date:** 18 November 2026
**Status of this document:** System rules. This document creates no coin, mints nothing, lists nothing, sells nothing, and spends nothing.

---

## 1. What registration is — and what it is not

### What registration is

Registration is the written record that a coin exists as a planned ScrollVerse work before it drops. It documents the coin's existence, its authorship, the time it was recorded, its history, its full description, its stated purpose, and its release date (TBD). It creates a paper trail through GitHub, artifacts, and websites, so that later — at launch, in a dispute, or in a review — anyone can see what was planned, when, by whom, and in what words. Registration is documentation. It is the record before the work.

### What registration is not

Registration is not a launch. It is not a sale. It is not a mint. It is not a pre-sale. It is not an offer to sell, and it is not a promise that a coin will ever launch. A registered coin may never launch. No token, no sale, no mint, and no token-as-reward is offered by the registration system, at any stage. Registration does not move money, does not create a token on any chain, and does not invite anyone to buy anything. The release date of every registered coin is TBD until the founder sets it after all three release gates have cleared (see §7).

---

## 2. Who can register

Only the founder, Chais Hill, can register a coin — acting as ScrollVerse LLC, the issuer entity.

There are no public submissions. No one else may submit a coin for registration, propose a coin on the founder's behalf, or register a coin in the founder's name. This is deliberate, for three reasons:

1. **Authorship must be certain.** Registration is a record of authorship. Only the founder can state that a coin is his work, what its description is, and what its stated purpose is.
2. **The record must stay clean.** Public submissions would fill the register with coins the founder never made, never approved, and never intends to launch. A register that anyone can write to proves nothing.
3. **The gates must hold.** Registration is the first step toward a launch that requires a written per-asset Howey analysis, SOL funding, and founder sign-off. If anyone could register, the gate sequence could be bypassed or confused. It cannot be.

Anyone who believes a coin should exist may tell the founder directly. That is a conversation, not a registration. Only the founder's decision creates a registration.

---

## 3. The registration process — step by step

### Step 1 — Submission (founder only)

The founder states the coin he wants registered: name, proposed ticker, art file and its source, description in his own words, and stated purpose. The submission is made to the registrar (Muse, working for the founder) in writing — in chat, in a file, or in a recorded instruction. No submission from any other person is accepted. If the founder's instruction is unclear on any required field (§4), the registrar asks the founder for the missing field. The registrar does not fill gaps by guessing.

**Who does it:** the founder submits; the registrar records the submission as received.

### Step 2 — Documentation

The registrar completes the full registration record using the required fields in §4. Every field is filled from the founder's own words and from the verified source files — the Pump.fun setup package, the coin library, and the Howey brief. The description is copied verbatim; it is never paraphrased, shortened, or improved. The art file and its source are recorded exactly as filed. The IP flag and the exclusions check (§4) are completed at this step: any third-party name, logo, or likeness in the name, art, or description is flagged, and any item on the never-register list (§9) stops the process at this step.

**Who does it:** the registrar drafts the record; the founder confirms the description and stated purpose are his words.

### Step 3 — Timestamp

The record is timestamped at the moment it is published in the three paper-trail places (§6): the GitHub commit, the artifact publication, and the website publication. The timestamp is the publication time, not the time the founder first thought of the coin and not the time the draft was written. Each of the three places carries its own timestamp, and all three are recorded in the registration entry. A record with no timestamp in all three places is not a complete registration.

**Who does it:** the registrar publishes and records the timestamps; the founder does not need to act at this step.

### Step 4 — Review

Before the entry is treated as final, the registrar checks it against this system: all required fields present, description verbatim, status set to Registered, release date TBD, exclusions check passed, IP flag correct, and the three paper-trail timestamps recorded. If anything is missing or wrong, the entry stays in draft and is not published. If the entry passes, it moves to publication. Review does not judge whether the coin is a good idea or whether it will launch — it judges only whether the record is complete and true.

**Who does it:** the registrar reviews; the founder confirms the entry before publication if he wishes to, and must confirm it if any field was corrected during review.

### Step 5 — Publication

The completed registration is published in the three paper-trail places (§6) and entered in the audit log (§6). Publication is the act that makes the registration real. From this point the entry is a historical record: it can be amended by appending a correction (§8), or marked Withdrawn or Abandoned (§9), but it is never rewritten and never deleted.

**Who does it:** the registrar publishes and logs; the founder is notified that the coin is Registered.

---

## 4. Required fields for every registration

Every registration must contain all of the following fields. A registration with a missing field is incomplete and is not published.

| Field | What goes in it |
|---|---|
| **Name** | The coin's name, exactly as the founder states it. |
| **Ticker** | The proposed ticker, exactly as the founder states it. Tickers are proposals until verified as available on Pump.fun at launch; a ticker is never treated as secured by registration. |
| **Art file + source** | The art file name and its full source path (workspace path and, where it exists, Pinata CID). Art must be the founder's own file or a file he holds the rights to use. Screenshot-only art is recorded as such and flagged as pending originals. |
| **Description (verbatim)** | The founder's description, copied word for word. Never paraphrased. Quoted in full. |
| **Stated purpose** | What the coin is for, in the founder's words — its purpose and use only. No language about financial outcomes. |
| **Supply** | Fixed supply as set by the platform. For Pump.fun Wave 1: 1,000,000,000 (1 billion), fixed by Pump.fun. |
| **Platform** | The launch platform, where known. For Wave 1: Pump.fun (Solana). |
| **Account** | The platform account the coin will be created from. For Wave 1: @DuneSimpleSock. |
| **Wallet** | The wallet address the coin will be created from. For Wave 1: `FpxkpRuL6RT5a4P48Wy4FVsRSLdAFsMABMjYKsWvZr64`. |
| **Status** | One of the four statuses only: Registered / Pending legal review / Pending funding / Launched (see §7). |
| **Registration timestamp** | The date and time of publication in each of the three paper-trail places (§5, §6). |
| **History** | The coin's history in brief: where the art and idea came from, when it first appeared, what it was first used for, and any earlier decisions about it (for example, a merch-only decision that does not cover a token). |
| **Documentation links** | Links or file paths to the source records: the setup package, the coin library entry, the Howey brief entry, the art file, and the GitHub, artifact, and website publication records. |
| **Release date** | Always TBD until the founder sets it after all three release gates have cleared. No date is ever entered before then. No estimated date, no target month, no season. TBD only. |
| **IP flag** | Yes or No. Yes if the name, art, or description uses any third-party name, logo, or likeness — including a team name or a living person's name or likeness. If Yes, the flag names the third party and the exposure, and the coin cannot move past Registered until the Howey analysis addresses it. |
| **Exclusions check** | A recorded check against the never-register list in §9, passed or failed, with the date of the check. A failed check stops registration. |

---

## 5. The timestamp standard

### What is timestamped

Three things are timestamped for every registration:

1. **The registration itself** — the date and time the completed entry was published.
2. **Each paper-trail publication** — the GitHub commit time, the artifact publication time, and the website publication time, recorded separately.
3. **Every later change** — each amendment (§8) and each status move (§7) carries its own timestamp. The original registration timestamp is never changed.

### How it is timestamped

- **GitHub commit:** the registration file is committed to the founder's GitHub (chaishillomnitech1). The commit's recorded time is the GitHub timestamp. The commit hash is recorded in the entry.
- **Artifact publication:** the registration is published as an artifact. The artifact's publication time is the artifact timestamp. The artifact identifier or link is recorded in the entry.
- **Website publication:** the registration is published on the website (ScrollVerse Atlas). The publication time shown on the site is the website timestamp. The page link is recorded in the entry.

No timestamp is written by hand into a file and called proof. The timestamp is the platform's own recorded publication time.

### How a timestamp is verified later

To verify a registration timestamp, check all three places and confirm they agree:

1. Open the GitHub commit by its recorded hash and read the commit time.
2. Open the artifact by its recorded identifier or link and read its publication time.
3. Open the website page by its recorded link and read its publication time.
4. Compare the three times with the timestamps recorded in the entry and in the audit log (§6).

If all three match the entry, the timestamp is verified. If any one is missing or disagrees, the registration is flagged in the audit log as unverified until the discrepancy is resolved by appending a correction (§8) — never by editing the original entry.

---

## 6. The paper-trail standard

Every registration must exist in three places. A registration that exists in fewer than three places is incomplete.

### Place 1 — GitHub

**What counts as proof:** a commit in the founder's GitHub (chaishillomnitech1) containing the registration file, with the commit hash and commit time recorded in the entry. The file must contain the full registration record (§4), not a summary.

### Place 2 — Artifacts

**What counts as proof:** a published artifact containing the registration record, with the artifact identifier or link and publication time recorded in the entry. The artifact must contain the full registration record, not a summary.

### Place 3 — Websites

**What counts as proof:** a published page on the website (ScrollVerse Atlas) containing the registration record, with the page link and publication time recorded in the entry. The page must contain the full registration record, not a summary.

### The audit log

A single audit log is kept for the Early Coins register. Every registration, amendment, status move, rejection, and withdrawal is entered in the log in order, with:

- the coin name and ticker;
- the action taken (registered, amended, status moved, rejected, withdrawn, abandoned);
- the date and time of the action;
- who took the action (founder or registrar, by name and role);
- the GitHub commit hash, artifact identifier, and website link for that action, where applicable.

The audit log is itself kept in the three paper-trail places. The log is append-only: entries are added, never edited or deleted.

---

## 7. Status transitions and the release gates

### The four statuses

The status field uses only these four values:

- **Registered** — the coin is documented and published in the three paper-trail places. Nothing else has happened.
- **Pending legal review** — the coin has been submitted for its written per-asset Howey analysis and the analysis is not yet signed.
- **Pending funding** — the written per-asset Howey analysis has cleared for that coin, and the coin is waiting for SOL funding in the wallet.
- **Launched** — the coin has been created on the platform. This status is set only after creation is confirmed on the platform.

No other status is used in the status field.

### What moves a coin between statuses

| Move | What must happen | Who approves it |
|---|---|---|
| Registered → Pending legal review | The registration is complete, and the founder directs that the coin be submitted for its written per-asset Howey analysis. The analysis is prepared with the AI law system and reviewed and signed by a licensed attorney. Free lawyers are approached first (Digital Currency and Ledger Defense Coalition, Rutgers Law clinics, Brooklyn Law BLIP, and the other free routes in the Howey brief addendum); pay-after routes are second. | Founder directs the submission. |
| Pending legal review → Pending funding | The written per-asset Howey analysis clears for that coin — signed by the licensed attorney, coin by coin, not as a blanket conclusion. If the analysis does not clear, the coin stays in Pending legal review, or goes back to Registered with the reason appended (§8). | Licensed attorney signs the clearance; founder confirms the move. |
| Pending funding → Launched | SOL funding is in the wallet in the amount needed to create the coin (~0.02 SOL per coin for Wave 1), and the founder signs off on that coin — name, ticker, art, and description confirmed. The coin is then created on the platform, and creation is confirmed on the platform before the status is set to Launched. | Founder signs off on that coin. |
| Launched | Terminal for the registration process. The entry remains as the historical record of the coin. | — |

### The release gates, in order

No gate may be skipped, and the order may not be changed:

1. **Written per-asset Howey analysis clears for that coin** — prepared with the AI law system, reviewed and signed by a licensed attorney, coin by coin. Free lawyers first; pay-after second.
2. **SOL funding in the wallet** — enough SOL deposited to the wallet to pay the creation cost for that coin.
3. **Founder sign-off on that coin** — the founder confirms that coin, by name, ticker, art, and description.

Only after all three gates have cleared may the founder set a release date. Until then, the release date stays TBD. A coin that has cleared gate 1 but not gate 2 is Pending funding. A coin that has cleared gates 1 and 2 but not gate 3 is still Pending funding. A coin that has not cleared gate 1 is Registered or Pending legal review — never Pending funding.

---

## 8. Amendment / correction process

History is never erased. Corrections append; they never rewrite.

When an entry needs correcting — a wrong file path, a misspelled name, a wrong timestamp, a description that was not verbatim, a status that was set in error — the correction is made as follows:

1. The error is stated in writing: what the entry says, what it should say, and why.
2. A correction note is appended to the entry, dated and timestamped, naming who made the correction and who approved it (the founder approves any correction to name, ticker, description, stated purpose, or release date; the registrar may correct a file path or link with the founder notified).
3. The original text stays in the entry, marked as superseded, with the correction note alongside it. The original is never deleted, overwritten, or edited in place.
4. The correction is published in the three paper-trail places (§6) and entered in the audit log (§6) with its own timestamp.
5. The entry's status does not change because of a correction, unless the correction itself is a status move under §7 — in which case the status move is recorded separately, with its own approval.

If a correction changes the description, the new description must again be the founder's words, copied verbatim, and confirmed by the founder.

---

## 9. Rejection / withdrawal

### What is never registered

The following are never registered as Early Coins, in any wave:

- The Code of Tawḥīd — free-only, never commercialised.
- Londyn — a child; never placed, sold, listed, or shown anywhere.
- Any coin using the Nipsey name or face.
- Any coin depicting prophets or living figures as new coins.
- Any coin whose art exists only as a phone screenshot, with no original file — until the originals are in hand.
- Any coin whose art is a real photo of real people, held as inventory only.
- Code, metadata templates, and archive snapshots — these are not coins.

A submission for any of the above is rejected at Step 2 of the process (§3). The rejection is recorded in the audit log with the reason, and no registration entry is created.

### What happens if a coin is abandoned or withdrawn

If the founder decides a registered coin will not launch — or if a coin is held indefinitely after review — the entry is not deleted. It stays as a historical record, with the following added:

- A disposition note appended to the entry, dated and timestamped: **Withdrawn** (the founder chose not to proceed) or **Abandoned** (the coin was left without a decision to proceed, and is no longer being pursued).
- The reason, in the founder's words where he gives one.
- The entry in the audit log recording the withdrawal or abandonment.

Withdrawn and Abandoned are disposition markers on a historical record. They are not statuses in the status field (§7), and they do not replace the coin's last status — the last status stays as it was, with the disposition noted alongside it. A withdrawn or abandoned coin is never re-registered as a new entry. If the founder later decides to pursue it again, the existing entry is reopened by appending a note, with a new timestamp, and the coin resumes from its last status.

---

## 10. Filled example — ScrollVerse (SVRS)

This is a complete registration entry, filled with the real facts from the source files. It is the template every other registration follows.

- **Name:** ScrollVerse
- **Ticker:** SVRS (proposed — verify availability on Pump.fun at launch)
- **Art file + source:** God Mode emblem. File: `~/workspace/merch/pinata/godmode-emblem.png` (also prepared as square 1000×1000 `~/workspace/digital-assets/pumpfun-pfp-godmode.png`). Pinata CID: `bafybeihdvxjyuhnc5i3uz4jenw72w5duqpwntkmzht6unpsemdnj4vc2fe`. Own IP — no third-party name, logo, or likeness.
- **Description (verbatim):** "The coin of ScrollVerse — music, film, fashion, and story worlds by Chais the Great. A share of every transaction goes back to the company and to environmental causes."
- **Stated purpose:** The coin of ScrollVerse — music, film, fashion, and story worlds by Chais the Great. A share of every transaction goes back to the company and to environmental causes.
- **Supply:** 1,000,000,000 (1 billion), fixed by Pump.fun.
- **Platform:** Pump.fun (Solana).
- **Account:** @DuneSimpleSock.
- **Wallet:** `FpxkpRuL6RT5a4P48Wy4FVsRSLdAFsMABMjYKsWvZr64`.
- **Coin website:** https://muse.ai/s/super-scrollverse-2-xtd6xtxncxwxuxj5z/0N8UONNtjBhZ0rrNB49dBusGU7KmQf1RYP59B4tVdS8 (ScrollVerse Atlas).
- **Status:** Registered.
- **Registration timestamp:** TBD — stamped at publication, in GitHub commit time, artifact publication time, and website publication time (§5). No timestamp is entered before publication.
- **History:** Lead coin of Wave 1. Art is the ScrollProof God Mode emblem, the founder's own original art, also used as the @DuneSimpleSock profile picture. The profile is live as of 18 November 2026. No other coin named ScrollVerse and no SVRS ticker exists on Pump.fun (verified 18 November 2026; the only ScrollVerse-adjacent coin found is "Doomscroll Goblin" ($SCROLL) by an unrelated creator). SVRS was chosen deliberately so no Solana coin shares a ticker with the founder's EVM token CHX, which is code only and not deployed on-chain. Creator fees ON. No coin has been created yet; the wallet holds $0.00 as of 18 November 2026 and no coin can be created until SOL is deposited.
- **Documentation links:** Setup package `~/workspace/digital-assets/pumpfun-setup-2026-11-18.md`; coin library `~/workspace/digital-assets/pumpfun-library/pumpfun-library.md`; Howey brief `~/workspace/legal/howey-brief-wave1-2026-11-18.md` (§5.1); Pump.fun profile https://pump.fun/profile/FpxkpRuL6RT5a4P48Wy4FVsRSLdAFsMABMjYKsWvZr64; ScrollVerse Atlas (coin website, above).
- **Release date:** TBD.
- **IP flag:** No. Own IP. No third-party name, logo, or likeness.
- **Exclusions check:** Passed 18 November 2026 — not on the never-register list in §9.

### Wave 1 — the other six coins

Registered in the same way, in launch order after SVRS, each with its own entry following the template above:

| # | Name | Ticker | Art | IP flag |
|---|---|---|---|---|
| 2 | Cyborg Brunson | CYBORG | `~/workspace/merch/pinata/brunson.png` | Yes — Knicks name and living player Jalen Brunson by name and likeness; needs a fresh explicit decision from the founder and Howey analysis addressing trademark and right-of-publicity exposure |
| 3 | The Anchor | ANCHOR | `~/workspace/merch/pinata/ewing.png` | Yes — Knicks name and living person Patrick Ewing by name and likeness |
| 4 | Floor General | GENERAL | `~/workspace/merch/pinata/frazier.png` | Yes — Knicks name and living person Walt Frazier by name and likeness |
| 5 | The Wing | WING | `~/workspace/merch/pinata/og.png` | Yes — Knicks name and living player OG Anunoby by name and likeness |
| 6 | The Tower | TOWER | `~/workspace/merch/pinata/towns.png` | Yes — Knicks name and living player Karl-Anthony Towns by name and likeness |
| 7 | The Assassin | ASSASSIN | `~/workspace/merch/pinata/king.png` | Yes — Knicks name and living person Bernard King by name and likeness |

Descriptions for coins 2–7 are verbatim from the coin library and the Howey brief, and are copied word for word into each coin's own registration entry. The earlier "build as-is" decision covered merch only, not a token launch, for coins 2–7.

### Future waves — to be registered in the same way

- **Wave 2 — AI Legion (11 coins):** Qubit (QUBIT), Socratica (SOCRATICA), Omnitech1 (OMNI1), Tatras (TATRAS), ZERO Flame (FLAME), King Solomon AI (SOLOMON), Lyrian Lion (LYRIAN), PSYCHE16 (PSYCHE16), QFS Oracle (QFS), Azurath (AZURATH), NŪR Cities AI (NUR). Tickers are proposals — verify availability at launch.
- **Wave 3 — Films (6 coins):** the 6 latest films, one coin each. Titles and art to confirm at launch.
- **Wave 4 — Music (4 coins):** Save Me (SAVE), How I Really Feel (HIRF), CUNNIN (CUNNIN), Goat (GOAT). Tickers are proposals — verify availability at launch.
- **Wave 5 — Books (4 coins):** ScrollVerse Manifesto (MANIFESTO), Book of the Journey (JOURNEY), Consciousness Mirror (MIRROR), Creator Books Desk (CREATOR). Tickers are proposals — verify availability at launch.

Every future-wave coin is registered under this same system, with the same required fields, the same timestamp and paper-trail standards, and the same three release gates. No future-wave coin is registered until its name, ticker, art, and description are confirmed by the founder.

---

## Source files

- `~/workspace/digital-assets/pumpfun-setup-2026-11-18.md`
- `~/workspace/digital-assets/pumpfun-library/pumpfun-library.md`
- `~/workspace/legal/howey-brief-wave1-2026-11-18.md`

*This document is a written system only. It does not publish, list, mint, spend, or contact anyone.*
