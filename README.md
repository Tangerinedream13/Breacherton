# Breacherton 🔐🪶

![Breacherton hero](assets/breacherton_hero.png)

_A Most Improper Breach — A Regency‑Era Cryptography & Authentication Learning Experience_

Dearest reader,

Welcome to Breacherton, the third installment in the Gemma & Rex series. This project uses a Regency‑era time‑travel mystery to teach cryptography, authentication, and message integrity. The story places modern cybersecurity concepts into a world of handwritten letters, wax seals, gossip columns, and social reputation — making abstract ideas tangible and dramatic.

**Core Question:** How do encryption, authentication, and integrity protect private communication from interception, impersonation, and alteration?

**Pitch / Story Premise**

- After the events of Toxic Match and Sexy‑Phish, Gemma and Rex find a corrupted compatibility file containing an encrypted artifact called the BridgerToken. Rex attempts to decode it, triggering a portal that deposits them into the season of Breacherton.
- Gemma is mistaken for a mysterious heiress; Rex is suspected of scandal. Forged letters, altered invitations, and a scandal column (published by Lady Whistlebyte) begin to upend the social season. Gemma and Rex must trace messages, decode ciphers, verify seals, and find the insider manipulating correspondence before the final ball.

**Title ideas**

- Primary: **Breacherton** — _Every secret leaves a trace._
- Alternates: BridgerToken, Breacherton: The Encrypted Season, Breacherton: Scandal in Plaintext

**Educational Goal**
Use story‑based puzzles to teach:

- **Confidentiality:** who can read a message?
- **Integrity:** has the message been altered?
- **Authenticity:** who really sent it?

**Three‑Act Structure**

**Act 1 — The Invitation**

- Artifact: `you_are_cordially_invited.key`
- Two invitations exist: a genuine and an altered copy. Players learn about authentication, signatures, and identity verification. The wax seal serves as a metaphor for a digital signature: possession of a seal is not proof of authorship.

# A Most Improper Breach — Breacherton

Dearest reader,

Welcome to Breacherton, the third installment in the Gemma & Rex series. This is an interactive story‑first experience in the style of *Sexy‑Phish* and *Toxic Match*: a time‑travel mystery set in a Regency season that teaches cryptography, authentication, and message integrity through playable puzzles.

Core Question

How do encryption, authentication, and integrity protect private communication from interception, impersonation, and alteration?

Pitch / Story Premise

- After the events of *Toxic Match* and *Sexy‑Phish*, Gemma and Rex find a corrupted compatibility file containing an artifact called the BridgerToken. Rex opens it — and they tumble into the season of Breacherton.
- Gemma is mistaken for a mysterious heiress; Rex is suspected of scandal. Forged letters, altered invitations, and a scandal sheet published by an anonymous columnist called Lady Whistlebyte begin to destabilize society. Gemma and Rex must trace messages, decode ciphers, verify seals, and uncover the insider manipulating correspondence before the final ball.

Title ideas

- **Breacherton** — Every secret leaves a trace.
- *BridgerToken*, *Breacherton: The Encrypted Season*, *Breacherton: Scandal in Plaintext*

Educational Goal

Teach cryptography and authentication concepts with story‑first, interactive puzzles that map directly to modern cybersecurity practices:

- Confidentiality — Who can read a message?
- Integrity — Has the message been altered?
- Authenticity — Who really sent it?

Three‑Act Structure

## Act 1 — The Invitation

- Artifact: `you_are_cordially_invited.key`
- Two invitations exist: one genuine and one forged. Players inspect seals, compare copies, and learn about identity verification and the limits of single‑factor proofs.

## Act 2 — The Secret Correspondence

- Artifact: `for_your_eyes_only.enc`
- Gemma receives an encrypted letter supposedly from Rex. Players decode simple historical ciphers (Caesar, substitution), compare keys, and learn symmetric vs asymmetric ideas and safe key exchange analogies.

## Act 3 — The Scandal Sheet

- Artifact: `integrity_compromised.txt`
- Private letters begin to appear in the scandal sheet. Players reconstruct delivery chains, compute fingerprints/hashes, and find evidence of tampering and an insider courier.

Gameplay — The Correspondence Desk

Players work at a correspondence desk containing:

- Invitations, letters, wax seals, cipher wheels, keys
- Torn fragments, delivery logs, gossip sheets, handwriting samples
- An offline assistant called L.A.C.E. (Letter Authentication and Cipher Examiner)

Actions map to modern concepts: verify seals (digital signatures), compare fingerprints (hashes), challenge the sender out‑of‑band (multi‑factor verification), and audit delivery chains (logging & provenance).

Key Learning Topics

- Cryptography: plaintext ↔ ciphertext, keys, ciphers
- Authentication: signatures, tokens, possession vs knowledge
- Integrity: hashing, checksums, tamper detection
- Attacks: man‑in‑the‑middle, impersonation, insider threats
- Key management and nonrepudiation

Characters

- Gemma — curious, socially smart investigator
- Rex — pragmatic, modern technologist
- Lady Whistlebyte — anonymous gossip columnist and plot driver
- The Courier — trusted messenger and suspect
- Duchess Ciphera — mathematician and codebreaker
- Lady Verity — society authority with social clout

Example Choices & Lessons

- Follow a summons immediately vs verify handwriting and logs: teaches out‑of‑band verification and cautious decision making.
- Compare invitation fingerprint with a verified copy: demonstrates the purpose of hashes/digital signatures.

Possible Endings

- Gemma identifies the attacker and preserves evidence.
- Gemma proves tampering but cannot identify the modifier.
- Rex walks into a trap after trusting a forged note.
- The BridgerToken remains corrupted, leaving a hook for future installments.

Branding Notes

- Favor parody and original branding: Breacherton alludes to the Regency genre without using copyrighted names or assets.
- Use visual metaphors: wax seals → signatures, torn letters → broken integrity, cipher wheels → encryption tools.

Next Steps

- Prototype Act 1 (the Invitation) as a playable puzzle.
- Draft the first Correspondence Desk puzzle with concrete artifacts, clues, and solution steps.

If you want, I will now scaffold the Act 1 prototype (UI + sample puzzles), or draft the playable Correspondence Desk puzzle content. Tell me which you prefer.
 
---

# Breacherton 🔐🪶

[![Breacherton hero](assets/breacherton_hero.png)](assets/breacherton_hero.png)

## A Regency‑Era Cryptography Learning Experience

Breacherton is an interactive, story‑first web experience in the vein of *Sexy‑Phish* and *Toxic Match*. It uses a Regency social season, forged letters, and scandal sheets to teach cryptography, authentication, and message integrity through playable puzzles and narrative choices.

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

CSCI‑364 Cybersecurity — UNC Asheville

---

## Run locally

```bash
git clone https://github.com/Tangerinedream13/Breacherton.git
cd Breacherton
# open or run the frontend dev server (example)
npm install
npm run dev
```

---

If you want, I can now scaffold an Act 1 prototype (UI + sample puzzles), or draft the playable Correspondence Desk puzzle content. Which do you prefer?
