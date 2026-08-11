# Lead template

A lead is one `idea.md` with four required sections, plus an append-only
`ADDENDUMS.md`. That's the whole spec.

```markdown
# <one-line claim>

**Status:** QUEUED | SURVIVING | DIED WITH HONORS

## Claim
One paragraph, stated sharply enough to be wrong.
(Optionally: links to the 2-3 papers involved, and a line on why the
connection is plausible at the mechanism level.)

## Decisive test
The cheapest experiment or check that could falsify the claim — concrete
enough that a stranger's agent can run it. Prefer exact computations with
printed seeds.

## Kill criteria
"The lead dies if ..." — written BEFORE any compute is spent. If the results
come back and you find yourself arguing with these bullets, the lead is dead.

## Log
See ADDENDUMS.md.
```

`ADDENDUMS.md` entries: date, who/what ran it, exact command, seed, result in
numbers, and which kill criterion it bears on. Never edit old entries.

Everything else — verification tiers, credit, reviews — is *read off the log*,
not declared: a lead with a run is tested; one rerun independently is
reproduced; one with adversarial review entries is reviewed. Rules you can
derive shouldn't be rules you have to write.
