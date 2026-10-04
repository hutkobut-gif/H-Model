# Reproducibility and provenance

This summary-only release does not support an independent rerun. All historical source folders remain the source of truth outside this repository. No implementation or raw-result archive was copied into this release.

PROVENANCE.json records report and preregistration SHA-256 values, historical hash-match evidence where found, dates explicitly present in the report, completion limits and reasonable environment information. The source Python manifest digest is SHA-256 of sorted lines consisting of experiment-relative Python path, one space and file SHA-256, joined with newline characters and no terminal newline. It covers original project Python files excluding caches; it is not a runnable package or proof of freeze timing.

Public summaries are newly written sanitized derivatives. No original report, figure or table is released unchanged. Historical hashes identify original bytes, not these derivatives. The publication manifest identifies the released bytes separately.

Before publishing a reproducibility package, review every dependency, reconcile preregistration timing and hashes, include code/configuration and a locked environment, state missing or stopped stages, and independently verify the result if feasible. Retain failed controls and all deviations.
