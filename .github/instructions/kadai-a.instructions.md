---
applyTo: "kadai-a/**"
---

**Problem statement:** Create a C program named `measure` that uses `clock_gettime(2)` to measure
the time taken to call `getpid(2)` once and 1000 times, respectively. Also write a report
(`report-a.md`) analyzing the cost of system calls based on the results.

*For the report, don't review the content — just check that the file (`report-a.md`) has been
created and that something is written.*

**Requirements:**

- The command `make measure` produces the executable.
- Use `clock_gettime(2)` with `CLOCK_MONOTOMIC` for the clock.
- Take the `tv_sec` field of `timespec` into account.
- Print both timing results clearly to stdout.
