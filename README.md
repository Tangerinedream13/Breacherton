# Breacherton 🔐🪶

[![Breacherton hero](assets/breacherton_hero.png)](assets/breacherton_hero.png)

## A Regency‑Era Cryptography Learning Experience

Breacherton is an interactive, story‑first web experience in the vein of _Sexy‑Phish_ and _Toxic Match_. It uses a Regency social season, forged letters, and scandal sheets to teach cryptography, authentication, and message integrity through playable puzzles and narrative choices.

## The Core Question

How do cryptography, authentication, and integrity protect private communication from interception, impersonation, and alteration?

---

## Project Overview

Breacherton is a choose‑your‑own‑adventure style web application that embeds cybersecurity lessons inside a Regency mystery. Rather than teaching by lecture, the experience uses artifacts, puzzles, and branching choices to make core security concepts memorable and relatable.

- Story‑first: characters, motives, social pressure
- Playable puzzles: decoding, verification, provenance tracing
- Narrative consequences that reveal security tradeoffs

---

## Story Structure

The experience unfolds in three acts, each built around an in‑game artifact:

**Act 1 — The Invitation**
`you_are_cordially_invited.key`

Two invitations: one authentic and one forged. Players inspect seals, compare copies, and learn the limits of single‑factor proofs and why provenance matters.

**Act 2 — The Secret Correspondence**
`for_your_eyes_only.enc`

An encrypted letter supposedly from Rex. Players break simple substitution ciphers, reason about key sharing, and map historical ciphers to modern symmetric/asymmetric concepts.

**Act 3 — The Scandal Sheet**
`integrity_compromised.txt`

Private letters appear in a scandal sheet. Players reconstruct delivery chains, compute fingerprints, and identify tampering and an insider courier.

---

## Target Audience

- Readers who enjoy romance and historical fiction
- Learners who dislike technical lectures but respond to stories
- Educators seeking a narrative, interactive approach to basic crypto

---

## Educational Focus

This project focuses on practical, beginner‑friendly lessons:

- Confidentiality: who can read a message?
- Integrity: has a message been altered?
- Authenticity: who sent it and how can we prove it?
- Key management, hashes, digital signatures, and secure channels

---

## Gameplay — The Correspondence Desk

Players interact with a desk that contains invitations, letters, wax seals, cipher wheels, torn fragments, delivery logs, and handwriting samples. Actions map to real concepts:

- Verify the seal → digital signatures
- Compare fingerprints → hashing
- Challenge the sender out‑of‑band → multi‑factor verification
- Audit delivery logs → provenance and logging

An in‑game assistant, L.A.C.E. (Letter Authentication and Cipher Examiner), offers hints and translates discoveries into modern cybersecurity language.

---

## Tech Stack (example)

- React
- Vite
- TypeScript / JavaScript
- Chakra UI or Tailwind CSS
- Netlify / Railway for hosting

---

## Creative Influences & Academic Foundation

- Regency fiction and serialized social season stories
- Research on cryptography education and story‑based learning
- Human factors in security and studies on integrity vs confidentiality

---

## References

- [Research on social engineering, cryptography education, and human factors] — to be collected and cited in the project.

---

## About

Built by Maria Haddon


---

## Run locally

```bash
git clone https://github.com/Tangerinedream13/Breacherton.git
cd Breacherton
# open or run the frontend dev server (example)
npm install
npm run dev
```
