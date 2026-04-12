---
applyTo: "kadai-f/**"
---

**Problem statement:** Research how to issue system calls directly on your machine's ISA (e.g.,
x86-64, aarch64) and write an assembly program named `hello` that prints "Hello, World!". Also write
a report (`report-f.md`) explaining how the system calls were invoked.

*For the report, don't review the content — just check that the file (`report-f.md`) has been
created and that something is written.*

**Requirements:**

- The command `make hello` produces the executable.
- Issue `write(2)` and `exit(2)` system calls in assembly.
