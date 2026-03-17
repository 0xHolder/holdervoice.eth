## Roadmap

HolderVoice is currently at its earliest stage: a single static page with one active proposal.
The roadmap below reflects a progressive build, prioritizing legal utility and community trust over features.

---

### ✅ Phase 0 — Proof of concept *(current)*

- [x] Single static HTML page (FR/EN)
- [ ] First proposal live: Series 118 – Books & Records demand
- [x] Proposal text published (FR + EN)
- [x] Proposal guidelines and reusable template drafted
- [x] GitHub repository initialized
- [x] AGPL-3.0 license

---

### 🔧 Phase 1 — Foundation *(next)*

> Goal: make the platform usable for any holder, for any Series.

- [ ] Multi-proposal support (one page per proposal, one folder per Series)
- [ ] Wallet connection (MetaMask / WalletConnect)
- [ ] Basic token gating: only holders of a specific Series token can submit or vote
- [ ] Community-sourced property status pages (`status.md` per Series)
- [ ] Document upload workflow via GitHub Pull Request
- [ ] `CONTRIBUTING.md` and submission rules published
- [ ] ENS resolution: holdervoice.eth pointing to IPFS deployment

---

### 🗳️ Phase 2 — On-chain voting

> Goal: votes are public, verifiable, and legally usable.

- [ ] Snapshot integration (strategy: ERC-20 balance per Series token)
- [ ] HolderVoice SBT deployed on Gnosis Chain (non-transferable membership badge)
- [ ] Batch airdrop SBT to all identified token holders
- [ ] `claim()` function for new holders joining after initial airdrop
- [ ] Vote results automatically archived in `/proposals/series-XXX/vote-result.json`
- [ ] Snapshot proposal export as PDF (legal package)

---

### 📁 Phase 3 — Community knowledge base

> Goal: every Series has a living, auditable dossier.

- [ ] Structured property pages (address, PIN, status, timeline, documents)
- [ ] Community timeline per Series (dates, events, official communications)
- [ ] Public document archive per Series (tax bills, court filings, screenshots)
- [ ] Lit Protocol integration: encrypted documents accessible only to Series token holders
- [ ] Search and filter by city, status, or Series number
- [ ] RSS or webhook feed for proposal updates

---

### ⚖️ Phase 4 — Legal coordination layer

> Goal: turn votes into structured legal packages.

- [ ] Auto-generated legal demand letter from vote result (§18-305 Delaware format)
- [ ] Timestamped and signed proposal PDF export (EAS attestation or IPFS hash)
- [ ] Legal contact directory (Delaware LLC specialists, by jurisdiction)
- [ ] Fee-sharing module for collective legal action funding
- [ ] Settlement tracker: status of each legal demand (pending / responded / litigated)

---

### 🌐 Phase 5 — Ecosystem expansion

> Goal: extend beyond one issuer, one jurisdiction.

- [ ] Support for non-Delaware jurisdictions (Panama S.A., etc.)
- [ ] Multi-issuer support
- [ ] Governance framework for the HolderVoice platform itself (meta-governance)
- [ ] SDK / API for third-party integrations
- [ ] Mobile-friendly PWA

---

### 💰 Legal Fund & Expense Tracking

> Goal: collective legal funding is transparent, auditable, and trustless.

- [ ] Multi-sig wallet per active proposal (Gnosis Safe)
  — contributors send funds directly to the Safe
  — withdrawals require M-of-N signatures (lead holders + counsel)
- [ ] Public contribution tracker: address, amount, date (on-chain, readable by all)
- [ ] Expense log published in `/proposals/series-XXX/expenses.md`
  — each expense: date, amount, recipient, purpose, tx hash
- [ ] Real-time fund balance visible on the proposal page
- [ ] Auto-refund logic: if proposal is cancelled or legal action not triggered,
  funds are returned pro-rata to contributors
- [ ] Optional: Juicebox or Gitcoin integration for gasless contributions

---


> Phases are indicative. Priority will follow community needs and legal urgency.
> There is no funding, no team, no deadline. This is a public good built incrementally.
