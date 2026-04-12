---
applyTo: "kadai-c/**"
---

**Problem statement:** Create two measurement programs `measure1` and `measure2` that time how long
it takes to copy a ~500KB file. read(2) and write(2) should be used for `measure1`, while fread(3)
and fwrite(3) should be used for `measure2`. Also write a report (`report-c.md`) comparing the
results.

*For the report, don't review the content — just check that the file (`report-c.md`) has been
created and that something is written.*

**Requirements:**

- The command `make measure1` and `make measure2` should produce the executables.
