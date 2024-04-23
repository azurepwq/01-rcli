# RCLI

rcli is a rust CLI tool.

## Q&A:

Q1: `2024-04-23 10:06:59 [ERROR] failed to open advisory database`?

A1: remove the `deny.toml` file in the repository root directory, and run `cargo deny init` to generate a new one.

Q2:
```
fix end of files.........................................................Failed
- hook id: end-of-file-fixer
- exit code: 1
- files were modified by this hook
```