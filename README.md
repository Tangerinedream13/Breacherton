# Breacherton 🔐🪶

*A Most Improper Breach — A Regency‑Era Cryptography & Authentication Learning Experience*

Dearest reader,

Welcome to Breacherton, the third installment in the Gemma & Rex series. This project uses a Regency‑era time‑travel mystery to teach cryptography, authentication, and message integrity. The story places modern cybersecurity concepts into a world of handwritten letters, wax seals, gossip columns, and social reputation — making abstract ideas tangible and dramatic.

**Core Question:** How do encryption, authentication, and integrity protect private communication from interception, impersonation, and alteration?

**Pitch / Story Premise**
- After the events of Toxic Match and Sexy‑Phish, Gemma and Rex find a corrupted compatibility file containing an encrypted artifact called the BridgerToken. Rex attempts to decode it, triggering a portal that deposits them into the season of Breacherton.
- Gemma is mistaken for a mysterious heiress; Rex is suspected of scandal. Forged letters, altered invitations, and a scandal column (published by Lady Whistlebyte) begin to upend the social season. Gemma and Rex must trace messages, decode ciphers, verify seals, and find the insider manipulating correspondence before the final ball.

**Title ideas**
- Primary: **Breacherton** — *Every secret leaves a trace.*
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

**Act 2 — The Secret Correspondence**
- Artifact: `for_your_eyes_only.enc`
- Gemma receives an encrypted letter allegedly from Rex. The player must determine authorship, confidentiality, and whether the message was tampered with. Start with substitution/Caesar ciphers and progress to modern analogies: keys, symmetric vs asymmetric, and safe key exchange.

**Act 3 — The Scandal Sheet**
- Artifact: `integrity_compromised.txt`
- Private information is published in the gossip column after messages are intercepted and modified. Players analyze delivery chains, hashes/checksums, and reconstruct original messages to identify a courier insider (a supply‑chain/insider risk lesson).

**Gameplay Mechanic: The Correspondence Desk**
Players use a desktop interface that contains:
- Letters, invitations, wax seals, cipher wheels, keys
- Torn fragments, delivery records, gossip sheets
- Handwriting samples and a timeline of handlers

Actions map to cybersecurity equivalents: verify the seal (digital signature), compare hashes (integrity checks), challenge the sender via out‑of‑band verification (multi‑factor/authentication), and reconstruct the delivery chain (audit/logging).

**In‑game Assistant: L.A.C.E.**
Letter Authentication and Cipher Examiner — an offline assistant on Gemma's damaged device that explains terms, compares seals, computes hashes, and translates historical actions to modern security concepts.

**Key Learning Topics**
- Cryptography: plaintext ⇄ ciphertext, ciphers, keys
- Authentication & identity: signatures, MFA, tokens
- Integrity: hashing, checksums, tamper detection
- Man‑in‑the‑middle, impersonation, insider threats
- Key management and nonrepudiation

**Characters & Roles**
- **Gemma** — the investigator with observational skill and social wit
- **Rex** — modern tech intuition, pattern recognition
- **Lady Whistlebyte** — anonymous gossip writer publishing scandals
- **The Courier** — trusted messenger and potential insider
- **Duchess Ciphera** — secretive mathematician who aids codebreaking
- **Lady Verity** — the authority figure who misleads trust

**Example Player Choices & Lessons**
- Immediately follow a summons vs verify handwriting and consult delivery records: illustrates out‑of‑band verification and cautious decision‑making.
- Compare invitation hash with a verified copy: shows file hashes/digital signatures in practice.

**Possible Endings**
- Gemma identifies the attacker and preserves evidence (best educational ending).
- Gemma proves tampering but cannot identify the modifier (lesson on limitations and the need for better logging/signing).
- Rex follows a forged invitation and is compromised (lesson on social engineering even when cryptography exists).
- The BridgerToken remains corrupted, leaving a hook for installment four.

**Branding & Messaging Guidance**
- Make the reference to Bridgerton clear but parody‑inspired and independent: avoid copying logos, exact characters, or show assets.
- Use visual metaphors for crypto: wax seals → signatures, torn letters → broken integrity, cipher wheels → encryption tools.

**Research & Evaluation Directions**
- Study learning outcomes for cryptography literacy and story‑based learning effectiveness.
- Evaluate whether players can distinguish confidentiality vs integrity vs authenticity after play.

**Next Steps**
- Prototype a single Correspondence Desk puzzle (Act 1) to validate pedagogy.
- Create art direction and UI mockups that map physical artifacts to digital analogues.

---

If you'd like, I can now:
- scaffold a small prototype for Act 1, or
- draft the first Correspondence Desk puzzle with sample artifacts and solution steps.

See the README in this repository: [README.md](README.md)
