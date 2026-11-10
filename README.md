# AI-assisted Mathematical Proofs 

**Start here:** [Subset Sum (PDF)](subset-sum/PROOF_0.4877.pdf)

## What the papers claim

### 1. Subset Sum in time O(2^{0.4877n}): a complete proof

Subset Sum asks whether some subset of given integers adds up to a target. The manuscript claims a randomized classical algorithm with running time

$$
O(2^{0.4877n})
$$

in the word-RAM model used by the cited OpenAI Subset Sum preprint. Its theorem states success probability at least 2/3, termination on every execution, and the stated asymptotic running-time bound for polynomially bounded input bit length. See Theorem 1 for the exact quantifiers and assumptions.

The argument uses results from the earlier paper and changes the alias procedure and checksum filters. The numerical checks cover specified inequalities; they are not a formal verification of the entire proof. The claimed running time remains exponential.

- [Read the paper](subset-sum/PROOF_0.4877.pdf)
- [LaTeX source, including verification scripts in Appendix D](subset-sum/PROOF_0.4877.tex)

### 2. Beeping Busy Beaver 51 and Peano Arithmetic

The manuscript claims that quasihalting of the specified 51-state beeping Turing machine is independent of Peano Arithmetic. It includes the process definition, machine table, and its proof arguments. The document relies on the Buchholz–Wainer classification theorem and a separate Rocq simulation development.

- [Read the original Markdown manuscript](beeping-busy-beaver-51/m51_selfcontained.md)

**Missing companion files:** `rocq51.tar.gz` (the Rocq simulation development required by the manuscript) and `checks51.tar.gz` (numerical checks) were attached to the original message but could not be retrieved for this upload. They are not included in this repository. The Busy Beaver package is therefore incomplete for reproduction.

### 3. Finite prime gaps from weighted Selberg sieves and pair penalties

The 6 November 2026 manuscript claims bounds H₂ ≤ 19,844, H₃ ≤ 1,357,780, H₄ ≤ 82,234,788, and H₅ ≤ 4,830,355,416, where Hₘ = lim inf (pₙ₊ₘ − pₙ). It combines sieve arguments with finite numerical certificates.

- [Read the paper](prime-gaps/prime_gap_verified_proof.pdf)
- [LaTeX source](prime-gaps/prime_gap_verified_proof.tex)
- [Certificates, logs, and reproduction code (ZIP, about 76 MiB)](prime-gaps/prime_gap_verified_certificates.zip)

The Busy Beaver materials were supplied by Avi Eisenberg on 30 October 2026; the prime-gap materials were supplied by him on 6 November 2026. The original manuscripts and supplied files are preserved unchanged. This records their provenance, not an assertion of authorship. These summaries describe the manuscripts' claims; this repository upload does not independently validate their proofs, and no supplied code was executed during the upload.

## Review and reproduction

Technical feedback is welcome in Issues. Please identify the paper, section or lemma, and the precise concern, correction or reproduction result. For computational results, include the command, dependency versions and relevant output.

