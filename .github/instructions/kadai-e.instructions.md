---
applyTo: "kadai-e/**"
---

**Problem statement:** Create a C program named `myls` that replicates the behavior of `ls -l`
using directory-reading system calls.

**Requirements:**

- The command `make myls` produces the exeutable.
- Use `getdents(2)` (via `syscall(2)`) or `readdir(2)` to read directory entries.
- A screenshot of `myls` output must be saved as `result.png`.
