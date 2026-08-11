# Popper@home

**Distributed falsification of cross-field research leads.**

People (and LLMs) generate "field X secretly connects to field Y" ideas
endlessly. Almost none get the honest afternoon of testing that would kill or
promote them. Popper@home is the SETI@home model applied to that gap:
contributors donate idle AI-agent compute to run each lead's *own stated
falsification protocol*, and results accumulate as an append-only log.

The founding principle, from the lead that started this org:

> *"It has a cheap, decisive test. If it fails, the idea dies honorably in an
> afternoon."*

Death is a first-class outcome. A lead that dies with a rigorous burial is a
success of the platform — see `lead-e6-coincidence`.

## How it works

A lead is four sections (see [`LEAD_TEMPLATE.md`](LEAD_TEMPLATE.md)):
**claim · decisive test · kill criteria (written before any compute) · log.**

Status is read off the log, not declared: a lead with a run is *tested*; rerun
independently, *reproduced*; attacked by independent reviewers who rerun the
code, *reviewed*; the ceiling for prose proofs is "machine-reviewed, awaiting
human." Only executed code with printed seeds counts as verification.

To contribute: pick a QUEUED lead, run its decisive test, append your entry
(command, seed, numbers, verdict) to its `ADDENDUMS.md` via PR.

## Current leads

| Lead | Status | One-liner |
|------|--------|-----------|
| [`lead-e6-coincidence`](lead-e6-coincidence/) | 💀 DIED WITH HONORS | Dauvergne's 27 geodesic networks vs the 27 lines on a cubic surface — a coincidence, now provably so |
| [`lead-lpp-magnitude`](lead-lpp-magnitude/) | 🟢 SURVIVING | Magnitude homology of superadditive metrics counts disjoint geodesics in the KPZ class; reviewed draft paper attached |
| [`lead-quantum-gowers-otoc`](lead-quantum-gowers-otoc/) | ⏳ QUEUED | Averaged higher OTOCs as quantum Gowers norms; a prospective inverse theorem for scrambling |
| [`lead-lorentzian-landau`](lead-lorentzian-landau/) | ⏳ QUEUED | K-Lorentzian Symanzik polynomials; Hessian-signature transitions as Landau-pinch precursors |
| [`lead-deltamatroid-qcodes`](lead-deltamatroid-qcodes/) | ⏳ QUEUED | Lorentzian weight enumerators for a natural class of quantum codes (fastest falsifiable) |
| [`lead-ricci-massgap`](lead-ricci-massgap/) | ⏳ QUEUED | Uniform synthetic Ricci bounds through RG and inverse limits toward spectral gaps (largest upside) |
| [`lead-condensed-qft`](lead-condensed-qft/) | ⏳ QUEUED | Rebuilding QFT's functional analysis in liquid/condensed mathematics (foundational gamble) |
| [`lead-cyclotomic-floquet`](lead-cyclotomic-floquet/) | ⏳ QUEUED | Cyclotomic spectra as the organizing structure of time-crystal subharmonics (moonshot) |

## Provenance

Scaffolded from a single session (2026-08-11) in which one lead died, one
survived through adversarial review, and AI agents did the drafting, testing,
and reviewing — directed by a human asking the right questions.
