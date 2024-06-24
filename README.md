# Mooncat C++ Standard

This repository contains all the standard files that should be included in any
MooncatCorps project. It also contains information on the Mooncat C++ code
style and standard.

One may notice that Mooncat tries to stay close to the latest C++ standard (
C++23 as of writing this document). The organization generally attempts
to stick to the latest stable releases of the tools at its disposal.
If a given project requires it, backports and / backwards compatibility
will be implemented.

## Files
This repository should be armed with:
- A `.clangd` file for LSP configuration
- A `.clang-flags` file for use with clang (`clang++ @.clang-flags`)
- A `.clang-format` file for autoformatting
- A `.clang-tidy` file for code quality control
- A `.gitignore` file for vcs exclusion
- A `.mooncat.toml` file for project management

