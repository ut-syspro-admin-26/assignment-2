---
applyTo: "kadai-b/**"
---

**Problem statement:** Create a C program named `mycp` that copies a file, implementing the basic
behavior of the `cp` command. Usage: `mycp (source) (target)`.

**Requirements:**

- The command `make mycp` produces the executable.
- Use system calls (e.g. `open`, `read`, `write`, `close`) for all file I/O — high-level library
  functions like `fopen` are not allowed.
- Partial writes must be handled correctly for `write(2)`.
- Check every system call's return value and do proper error handling on failure.

**Optional Goals**

- Preserve the source file's permissions on the target file.
