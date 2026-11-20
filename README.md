# DEBRIEF-math-grh-masullo

A DEBRIEF mission record (protocol https://github.com/Nervous-Machine/DEBRIEF) for **The claimed proof of the Generalized Riemann Hypothesis by Alessandro Maria Masullo, a 940-page draft released on 20 November 2026**.

**Standing.** Certified 0. Accepted 0. Refuted 0. Open gaps 5. This record is at tier zero: the claim and its public artifacts are pinned, the checks still owed are listed, and nothing has been run or read yet. The first contribution is open.

This claim is on the public claims board, https://math-board.nervousmachine.com, which shows its stage, who has contributed, and what it needs next.

## The problem

The Riemann Hypothesis says every zero of the Riemann zeta function with real part strictly between zero and one has real part one half. The Generalized Riemann Hypothesis says the same of every Hecke L-function of every number field, so for every Dirichlet L-function in particular. The draft's stated generality is all number fields and all unitary Hecke characters.

Source: https://www.claymath.org/millennium/riemann-hypothesis/ (posed: Riemann (1859) for the zeta function; the generalization to Dirichlet and Hecke L-functions followed in the decades after).

## The claim

**Alessandro Maria Masullo**, using none; the announcement says the work is all human, with no AI, submitted 2026-11-20 at https://math216.wordpress.com/2026/11/20/hurried-announcement-alessandro-masullo-grh/.

The draft builds a trace formula for Hecke L-functions of a number field from adelic theta functions, idelic zeta functions, Schauder bases on modulated groups and nuclear operators on Hardy-Sobolev spaces, and labels that formula 12.5.1.1, "the Main Theorem of this work". Chapter 13 is to deduce from it that the zeros lie on the half line, with a multiplicity bound; Chapter 14 discusses why the method does not extend to function fields. As released, Chapter 13 contains the headings of three sections, a restatement of the trace formula with a footnote reading "Correct statement", and a result labelled "Divisor of L(s, chi)" whose statement is a footnote reading "Insert statement" followed by "State and prove the Main Theorems". So the draft states no result about the zeros. The preface says the introduction is unfinished and that the author was to spend a year at Stanford polishing the text. A Lean 4 formalization effort by a third party (github.com/mccorvie/riemann-masullo) started the day of release, logs ten appendix statements it reports as false as stated and about thirty imprecisions, none yet reviewed by a specialist, and paused the same day after a report on the Lean Zulip that an AI-assisted reading found a counterexample to the trace formula; that counterexample has not been posted.

Artifacts, pinned:

- a PDF write-up: https://math216.wordpress.com/wp-content/uploads/2026/11/the-music-of-the-primes.pdf (sha256 e039d3f6cf0a4b14f03c7edb85097752dd65c0a2fe543c76fe992be234f97bf5, 6756996 bytes, fetched 2026-11-20)

Status on the problem page as of 2026-11-20: a draft attached to a blog post; no preprint server, no journal, no public referee report.

## What is owed

Each open gap is in `ASKS.md` with what closes it and who could act. In order:

1. **No formal deduction exists for the claimed proof** (EG1): A formalization of the main theorem, with the statement written by someone other than the prover.
2. **No independent mathematician has reported reading the proof, and there is no referee report** (EG2): Someone in the field reads it and says, under their name, what holds and what does not.
3. **The deduction about the zeros is not yet written: Chapter 13 is headings and placeholders, as the author's preface says** (EG3): The statement of the main result and its deduction from the trace formula, in the draft.
4. **The trace formula labelled 12.5.1.1 is disputed and the reported counterexample has not been posted** (EG4): The counterexample, in public, and two readings of it.
5. **Ten appendix statements are reported false as stated, by an AI agent, and no specialist has checked the reports** (EG5): A reading of the ten errata entries, signed or refused one by one.

## Contributing

- **Rerun**: there is nothing to run yet. The draft has no formal deduction; the first formalization of its main statement, by anyone, is a `claim` cycle and opens the rerun gap.
- **Read**: a trace (reading guide) does not exist yet. Writing one is itself a `trace` cycle. Once it exists, the **Semantic read** form takes signatures and refusals.
- **Anything else**: open a plain issue.

Rules and templates: https://github.com/Nervous-Machine/DEBRIEF/blob/main/CONTRIBUTING.md. Every contribution is one dated cycle under your own name and goes into `CITATION.cff` and the next release.

## Layout

```
ledger/grh-masullo.json   the ledger (protocol 0.1.0)
claim.yaml            the pinned claim this record was opened from
SCORECARD.md / ASKS.md  generated from the ledger
source/               hash of the PDF and of the announcement page, with fetch time
cycles/               contributed cycles, one file each
```

## Words

This record never calls the claim proved, verified or a theorem. It records what was claimed, what was checked by whom under what rule, and what is still open. Nothing here has standing until a cycle gives it one.
