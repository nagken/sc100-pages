# Common Pitfalls - SC-100

> Frequent confusions, traps, and "gotchas" that cause wrong answers on the exam.

### Treating Zero Trust as a project, not a program

ZT is a multi-year iterative practice; a single migration will not finish it.

### Designing two SOCs (cloud + on-prem)

Fuse them. Sentinel + XDR + DfC ingest both worlds.

### Ignoring CAF Secure when designing landing zones

Landing zones include identity + policy + network from day 1.

### Forgetting MCSB is the new baseline

ASB is deprecated. New built-in policy = MCSB.

### Confusing CMK and BYOK in HSM contexts

CMK = you own the key in Azure HSM. BYOK = you imported the material. HYOK = key never leaves on-prem HSM.


---

[Master Index](00-MASTER-INDEX.md)
