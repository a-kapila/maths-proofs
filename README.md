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

## Review and reproduction

Technical feedback is welcome in Issues. Please identify the paper, section or lemma, and the precise concern, correction or reproduction result. For computational results, include the command, dependency versions and relevant output.

