---
applyTo: "kadai-d/**"
---

**Problem statement:** Create a C program named `mywc` that reads a text file and counts lines,
words, and bytes — implementing the basic behavior of the `wc` command. Usage: `mywc (source)`.

**Requirements:**

- The commnad `make mywc` produces the executable.
- Use system calls (e.g. `read`) for file I/O — high-level library functions are not allowed.
- Read the file in chunks into a buffer (not byte-by-byte).
- Output format must match `(lines) (words) (bytes) (filename)` (spacing may be approximate).
